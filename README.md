# Recently Played Songs In-Memory Store

This Python project implements an in-memory store for recently played songs. It provides a `RecentlyPlayed` class that allows you to store a list of recently played songs per user, with a fixed capacity. When the store becomes full, it automatically eliminates the least recently played songs.

## Project Structure

The project has the following directory structure:

my_app/
recently_played.py

tests/
test_recently_played.py


- `my_app/` directory contains the implementation of the RecentlyPlayed class in the `recently_played.py` file.
- `tests/` directory contains the test code in the `test_recently_played.py` file.

## Installation and Execution

1. Clone the repository: 

    https://github.com/BipashaB26/QA_Answer_TestVagrant

2. Change into the project directory: 

    cd QA_Answer_TestVagrant

3. (Optional) Set up a virtual environment:
  ```  
    python3 -m venv venv
    source venv/bin/activate
  ```

4. Install the required dependencies:
  ```
    pip install -r requirements.txt
  ```

5. Run the tests:
  ```
    python -m pytest
  ```
    - This will execute the `test_recently_played.py` file and verify the functionality of the RecentlyPlayed class

6. Use the RecentlyPlayed class in your own code by importing it:

```python
from my_app.recently_played import RecentlyPlayed

#Create an instance of RecentlyPlayed and use its methods
```
 

