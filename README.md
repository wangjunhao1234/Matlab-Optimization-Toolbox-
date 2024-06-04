# MATLAB 优化工具箱和全局优化工具箱
MATLAB 提供了两个主要的工具箱来处理各种类型的优化问题：优化工具箱（Optimization Toolbox）和全局优化工具箱（Global Optimization Toolbox）。这两个工具箱提供了一系列强大的算法，适用于从简单的线性规划到复杂的全局优化问题。

## 优化工具箱（Optimization Toolbox）
优化工具箱提供了广泛的函数用于求解线性、非线性、有约束和无约束以及二次规划问题。主要特性和函数包括：
- **linprog** - 线性规划问题的求解。
- **intlinprog** - 混合整数线性规划问题的求解。
- **quadprog** - 二次规划问题的求解。
- **fmincon** - 有约束的非线性问题的求解。
- **fminunc** - 无约束的非线性问题的求解。
- **lsqlin** - 线性最小二乘问题的求解。
- **lsqnonlin** - 非线性最小二乘问题的求解。
- **lsqcurvefit** - 曲线拟合问题的求解。
- **多目标优化** - 提供多目标优化算法。
该工具箱特别适用于需要精确解决优化问题的工程师和科研人员，包括产品设计、流程优化、资源管理等应用领域。

## 全局优化工具箱（Global Optimization Toolbox）

全局优化工具箱扩展了 MATLAB 的优化能力，提供了算法和函数来找到问题的全局最优解。主要特性和函数包括：
- **ga** - 遗传算法，用于处理各种优化问题。
- **simulannealbnd** - 模拟退火算法，用于解决全局优化问题。
- **particleswarm** - 粒子群优化，用于全局优化。
- **patternsearch** - 模式搜索算法，不使用问题的导数信息。
- **surrogateopt** - 替代模型优化，用于计算代价高昂的函数优化。
- **GlobalSearch** 和 **MultiStart** - 全局搜索和多起点搜索，提高寻找全局最优解的可能性。
全局优化工具箱特别适合处理可能包含多个局部最优解的复杂问题，如生物信息学、化学工程、金融模型等领域中的应用。
