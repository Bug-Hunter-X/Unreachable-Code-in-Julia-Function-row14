# Unreachable Code in Julia

This repository demonstrates a common but easily missed error in Julia: unreachable code within a function.  The `bug.jl` file contains a function with unreachable code following conditional returns.  The `bugSolution.jl` demonstrates the corrected version.

This type of error can lead to unexpected behavior or maintenance difficulties, especially in larger codebases.  Understanding how Julia's control flow works helps prevent these issues.