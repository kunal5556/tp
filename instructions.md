GitHub - kunal5556/LRET
Contribute to kunal5556/LRET development by creating an account on GitHub.
github.com

GPU TESTING

Repo - https://github.com/kunal5556/LRET.git

Branch - feature/framework-integration

Directory - GPU_Debugging_and_Testing

Dependencies installation :
    Automated
        Linux: Run the following script:

GPU_Debugging_and_Testing/setup_and_run_hardware_tests.sh

        Windows: Run the following script:

GPU_Debugging_and_Testing/setup_and_run_hardware_tests.ps1


The above scripts automatically run the python test script
(run_hardware_dependent_tests.py, prints GPU metrics and logs if tests pass, and errors if tests fail) in csv files for further use









































GitHub - kunal5556/LRET
Contribute to kunal5556/LRET development by creating an account on GitHub.
github.com

Pennylane Benchmarking

Repo - https://github.com/kunal5556/LRET.git

Branch - pennylane-documentation-benchmarking

Directory - benchmarks/pennylane

Dependencies installation :
1. Manual - benchmarks/pennylane/REQUIREMENTS.md

(if want to install dependencies manually. Contains list of all dependencies. Not a script, will have to open file and copy paste each command)

2. Automated - Run as — python setup_pennylane_env.py

benchmarks/pennylane/setup_pennylane_env.py


Scripts : Run as — python ...
1. benchmarks/pennylane/pennylane_4q_50e_25s_10n.py
2. benchmarks/pennylane/pennylane_8q_100e_100s_12n.py
3. benchmarks/pennylane/pennylane_8q_200e_200s_15n.py
4. benchmarks/pennylane/pennylane_4q_50e_25s_10n_row.py
5. benchmarks/pennylane/pennylane_8q_100e_100s_12n_row.py
6. benchmarks/pennylane/pennylane_8q_200e_200s_15n_row.py
7. benchmarks/pennylane/pennylane_4q_50e_25s_10n_hybrid.py
8. benchmarks/pennylane/pennylane_8q_100e_100s_10n_hybrid.py
9. benchmarks/pennylane/pennylane_8q_200e_200s_15n_hybrid.py
10. benchmarks/pennylane/pennylane_4q_50e_25s_10n_compare_all.py
11. benchmarks/pennylane/pennylane_8q_100e_100s_12n_compare_all.py
12. benchmarks/pennylane/pennylane_8q_200e_200s_15n_compare_all.py
13. benchmarks/pennylane/compare_modes_comparison.py

