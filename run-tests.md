# Test Runner Package

## Run tests

There is an executable file in the `saeghe.config.json` file for the Test Runner package.
Therefore, you can use the executable file for running tests after building the project.

> **Note**  
> For more information about executable files, please read [customization documentation](https://saeghe.com/documentations/customization)

Based on the config file, you can run tests by running the `test-runner` file:

```shell
cd builds/development
./test-runner
```

### Filtering tests

You may need to filter the test file that you want to run. 
In this case, you can use the `filter` argument for filtering the test file that you want to run.

```shell
./test-runner --filter=SampleFileTest
```
