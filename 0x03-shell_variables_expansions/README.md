# Shell init files, variables and expansions

Project done during **Full Stack Software Engineering studies** at **ALX**. It aims to learn __about__:

* The difference between a local and a global variable.
* What is a reserved variable.
* How to create, update and delete shell variables.
* What are the roles of the following reserved variables: `HOME`, `PATH`, `PS1`.
* What are special parameters.
* The `alias` Command.

## Files


All of the following files are scripts.



> * [0-alias](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/0-alias)
>> A script that creates an alias.
>>> - _Name:_ `ls`
>>> - _Value:_ `rm *`
------------------
> * [1-hello_you](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/1-hello_you)
>> A script that prints `hello user`, where user is the current Linux. user.
------------------
> * [2-path](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/2-path)
>> Add `/action` to the `PATH`.
>>> `/action` _should be the last directory the shell looks into when looking for a program._
------------------
> * [3-paths](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/3-paths)
>> A script that counts the number of directories in the `PATH`.
------------------
> * [4-global_variables](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/4-global_variables)
>> A script that lists environment variables.
------------------
> * [5-local_variables](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/5-local_variables)
>> A script that lists all local variables and environment variables, and functions.
------------------
> * [6-create_local_variable](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/6-create_local_variable)
>> A script that creates a new __local__ variable.
>>> - _Name:_ `BEST`
>>> - _Value:_ `School`
------------------
> * [7-create_global_variable](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/7-create_global_variable)
>> A script that creates a new __global__ variable.
>>> - _Name:_ `BEST`
>>> - _Value:_ `School`
------------------
> * [8-true_knowledge](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/8-true_knowledge)
>> A script that prints the result of the addition of `128` with the value stored in the environment variable `TRUEKNOWLEDGE`, followed by a new line.
------------------
> * [9-divide_and_rule](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/9-divide_and_rule)
>> A script that prints the result of `POWER` divided by `DIVIDE`, followed by a new line.
>>> `POWER`, `DIVIDE` _are environment variables_. 
------------------
> * [10-love_exponent_breath](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/10-love_exponent_breath)
>> A script that displays the result of `BREATH` to the power `LOVE`, followed by a new line.
>>> `BREATH`, `LOVE` _are environment variables_.
------------------
> * [11-binary_to_decimal](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/11-binary_to_decimal)
>> A script that converts a number from base `2` to base `10`, and display it in base `10`, followed by a new line.
>>> The number in base `2` is stored in the environment variable `BINARY`.
------------------
> * [12-combinations](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/12-combinations)
>> A script that prints all possible combinations of two letters, except `oo`.
>>> - _Letters are lower cases, from_ `a` _to_ `z`.
>>> - _One combination per line_.
>>> - _The output alpha ordered, starting with `aa`_.
------------------
> * [13-print_float](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/13-print_float)
>> A script that prints a number with two decimal places, followed by a new line.
>>> _The number will be stored in the environment variable_ `NUM`.
------------------
> * [100-decimal_to_hexadecimal](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/100-decimal_to_hexadecimal)
>> A script that converts a number from base `10` to base `16`, and display it in base `16`, followed by a new line.
>>> _The number in base `10` is stored in the environment variable_ `DECIMAL`.
------------------
> * [101-rot13](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/101-rot13)
>> A script that encodes and decodes text using the rot13 encryption.
>>> _Assume ASCII_.
------------------
> * [102-odd](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/102-odd)
>> A script that prints every other line from the input, starting with the first line.
------------------
> * [103-water_and_stir](https://github.com/Moh-A-Mahdi/alx-system_engineering-devops/blob/master/0x03-shell_variables_expansions/103-water_and_stir)
>> A script that adds the two numbers stored in the environment variables `WATER` and `STIR` and prints the result.
>>> - `WATER` _is in base_ `water`.
>>> - `STIR` _is in base_ `stir.`.
>>> - _The result is in base_ `bestchol`.
