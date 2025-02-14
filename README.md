# Fingerprinting vs Profiling

Our dependence on data-driven applications continues to grow across various sectors, including sensitive domains such as healthcare, social media, and transportation. Due to this, robust mechanisms are essential to safeguard user privacy and ensure the responsible use of personal information. While differential privacy (DP) offers a promising approach to enhance data protection, its ability to fully safeguard privacy versus simply mitigating re-identification remains debated.  DP can significantly reduce the risk of re-identification and data leakage. However, this alone is insufficient, as much user data is used for profiling—inferring sensitive information about individuals.  We conducted a small evaluation to assess the impact of DP on profiling model accuracy. Our results indicate that even with DP applied, these models retain an average of 80% accuracy.

## Run the evaluation

The complete code for this project is available in the Jupyter Notebook [main](main.ipynb).

All necessary dependencies are listed in [requirements](requirements.txt).

To run the code, simply create a Python environment, install the required packages, and execute the notebook.

## Author

* [**Catarina Silva**](https://github.com/catarinaacsilva)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

