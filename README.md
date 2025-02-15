# Checkerboard Project

This project generates a checkerboard pattern using Python and Matplotlib. The color of the checkerboard can be customized.

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x
- NumPy
- Matplotlib

You can install the required libraries using the following command:

`pip install numpy matplotlib`

## How to Run the Project

1. Clone this repository to your local machine:

   `git clone https://github.com/your-username/your-repository-name.git`

2. Navigate to the project directory:

   `cd your-repository-name`

3. Install the required libraries:

   `pip install numpy matplotlib`

4. Run the Python script:

   `python3 checkerboard.py`

5. View the result:
   - After running the script, a checkerboard pattern will be displayed.

## Customizing the Checkerboard Color

To change the color of the checkerboard, modify the `cmap` parameter in the `plt.imshow()` function in the `checkerboard.py` file. For example:

```python
plt.imshow(board, cmap="inferno")  # Replace "inferno" with any other colormap
