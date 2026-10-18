# studio-runner

A tiny, content-free runner. The workflows here check out a private project with a token kept in this repository's encrypted secrets, run its jobs, and write the results back to that private project.
Nothing from the jobs is printed in the public logs (the full logs are stored in the private project).
