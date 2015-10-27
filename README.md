# spim-grader
Quick python script to grade MIPS homework submissions
Uses python's subprocesses library to spawn processes to test MIPS programs using spim's command-line option. Returns results based on success/syntax error/invalid address error/hanging (pretty sure that's all there is).
Runs all sample test files in /samples against all submitted homeworks in /submissions. Stores output in /results.
/samples and /submissions must exist for script to run.
See [/samples/.example](/samples/.example) and [/submissions/.example](/samples.example) for instructions on specific input.
