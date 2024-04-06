def generate_readme():
    # Content for the README
    readme_content = """
# Developer Compensation Analysis

This project analyzes the relationship between employment status and yearly compensation among developers in the United States.

## Description

The analysis utilizes data from the Stack Overflow Developer Survey to examine how different employment statuses correspond to average yearly compensation.

## Statistical Analysis

The analysis includes statistical measures such as mean, standard deviation, median, minimum, and maximum yearly compensation for each employment status.

## Visualization

Two types of visualizations are used:
- A bar chart displaying the mean yearly compensation with error bars representing the standard deviation.
- A line chart showing the mean compensation for each employment status.

## Requirements

- Python 3.x
- Pandas
- Matplotlib

## Usage

1. Clone the repository.
2. Place the survey data file (`survey_results_public.csv`) in the same directory as the script.
3. Run the script.
4. View the generated visualizations and statistical information.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
"""

    # Write the content to README.md file
    with open("README.md", "w") as readme_file:
        readme_file.write(readme_content)

    print("README.md file generated successfully.")

# Generate README
generate_readme()
