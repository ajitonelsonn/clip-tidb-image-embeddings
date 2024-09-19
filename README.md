<div align="center" style="display: flex; align-items: center; justify-content: center; flex-wrap: wrap;">
  <img src="images/lafaek_ai.png" alt="LAFAEK AI Logo" width="70" style="margin-right: 20px;"/>
  <span style="font-size: 28px; font-weight: bold; margin: 0 30px;">LAFAEK AI - TiDB FAH 2024</span>
  <img src="images/tidb.png" alt="TiDB Logo" width="120" style="margin-left: 20px;"/>
</div>

---

# CLIP-TiDB Image Embeddings

This project demonstrates how to generate image embeddings using the CLIP model and store them in TiDB Serverless with Vector Search. This approach is part of our submission for the TiDB Future App Hackathon 2024 under the LAFAEK AI team.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [More Information](#more-information)

## Installation

### Step 1: Clone the Repository

Clone this GitHub repository to your local machine:

```bash
git clone https://github.com/ajitonelsonn/clip-tidb-image-embeddings.git
```

Navigate to the project directory:

```bash
cd clip-tidb-image-embeddings
```

### Step 2: Create a Virtual Environment

First, create a virtual environment to manage your dependencies:

```bash
python3 -m venv venv
```

Activate the virtual environment:

- On macOS/Linux:
  ```bash
  source venv/bin/activate
  ```
- On Windows:
  ```bash
  .\venv\Scripts\activate
  ```

### Step 3: Install Requirements

Install the required Python packages using `pip`:

```bash
pip install -r requirements.txt
```

This will install all the necessary libraries, including `torch`, `clip`, `mysql-connector-python`, `pandas`, and others required for running the Jupyter notebook.

## Usage

After setting up your environment and installing dependencies, you can start working with the notebook provided in the repository. The notebook walks you through the following:

1. Importing necessary libraries.
2. Loading the CLIP model for generating image embeddings.
3. Connecting to TiDB Serverless to store and retrieve embeddings.
4. Batch processing images and storing their embeddings in the database.
5. Performing vector searches to find similar images.

To run the notebook:

```bash
jupyter notebook
```

Open the `clip_tidb_image_embedings.ipynb` file in the Jupyter Notebook interface and follow the instructions provided.

## Contributing

We welcome contributions to this project. If you find a bug or have a feature request, please open an issue on GitHub. Feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## More About LAFAEK AI

1. **Lafaek AI Landing Page MVP**  
   The MVP landing page for Lafaek AI, created for the hackathon, is available. Visit the repository here: [GitHub Link](https://github.com/ajitonelsonn/TiDB_FAH_2024_Vlafaekai) and check out the demo here: [Vercel Demo](https://lafaekaitidb.vercel.app/index.html).

---

Happy coding! 🎉
**Made from 🇹🇱Timor-Leste with ❤️**
