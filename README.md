# Class Assignment #3 - Unit Testing and Continuous Integration

This assignment is building on your previous assignment for developing the HF-SCF code. Here you will add pytest unit tests to test each of the functions in SCF.py.

## The Assignment

Submit a pull request that has each function in `SCF.py` tested in the file `tests/SCF/test_SCF.py` sufficiently that you can ensure the correctness of the function. You can use the hints in the README from the previous assignment to develop tests. 

Steps:

1. Fetch upstream on your current fork to obtain the changes made to the main repository to enable testing. Also you will need to `pip install -r requirements.txt` again to ensure that the new modules added are in your environment.
2. Edit the `tests/SCF/test_SCF.py` file to add the tests. 
3. Commit your changes to the fork, this will automatically update any pull requests that you have made for the previous assignment.

**Note:** The current Continous integration is testing for PEP8 compliance, and will fail on the pull request checks if the code is not to spec.

Hints:
1. To test whether your code is compliant, you can run `pycodestyle -r <filename>`, this will give you a readout of the non-compliance issues that you can fix before committing.
2. To test your unit tests, in the main directory, you can just run `pytest` and you should get a read out. You will need to ensure that your unit tests are working before submitting completing the task, as success will be passing all of the unit tests on every function.

