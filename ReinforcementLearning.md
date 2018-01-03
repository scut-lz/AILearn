时间差分学习(Temporal-Difference learning, TD Learning)：
    base：
        动态规划算法(DP)：
            1.  需要环境模型（状态转移概率Psa）
            2.  状态值函数的估计是自举的(bootstrapping，
                所谓bootstrpping本意是指自举，此处是指当前值函数的计算用到了后继状态的值函数。即用后继状态的值函数估计当前值函数。),
                当前状态值函数的更新依赖于已知的状态值函数
        蒙特卡洛方法(MC)
            1.  可以从经验中学习，不一定需要环境模型
            2.  状态值函数相互独立
            3.  只适用于episode tasks.
    综合考虑，理想的强化学习应该是：
            1.  不需要环境模型
            2.  不局限于episode tasks,可以适用于连续的任务
    时间差分学习结合了DP和MC的优点
    
    
    
    
