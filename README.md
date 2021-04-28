# Installing and Testing Cython #

In the following workshop, we will be using Cython to write compilable parallel code. To prepare, please complete the following steps.

1. Install Cython using pip3 (pip3 install Cython) or your preferred package manager.

2. In the folder containing this README:

3. Execute the command:

    ```
    python3 setup.py build_ext --inplace
    ```
		
4. Check that a file starting with "helloworld" and ending with ".so" (Unix) or ".pyd" (Windows) has been created.

5. Start the Python 3 interpreter:

    ```		
    python3
    ```

6. Import the ".so" or ".pyd" file (it's a python module):

    ```		
    import helloworld
    ```

    This should result in the output:

    ```
    "Hello World"
    ```

If you encounter an error that prevents you from completing the above steps, please send me an email (edric.matwiejew@research.uwa.edu.au) with the error message, and we will endeavour to correct the issue at the start of the workshop.