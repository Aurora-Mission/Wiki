# Aurora Mission's Wiki

## Documentation

The official documentation for this project is hosted at:

[https://aurora-mission-wiki.readthedocs.io/en/latest](https://aurora-mission-wiki.readthedocs.io/en/latest)

## Contributing to Documentation

Follow these steps to set up and contribute to the project documentation.

### Prerequisites

- Python 3.x
- Git

### Setup Process

#### 1. Clone the Repository

```bash
git clone https://github.com/Aurora-Mission/Wiki.git
cd Wiki
```

#### 2. Create a Virtual Environment

```bash
# Create a virtual environment
python3 -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

#### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### Building Documentation

#### Build HTML Documentation

```bash
make html
```

The built documentation will be available in `build/html/`. You can open `index.html` in your browser to preview your changes locally.

#### Clean the Build

If you need to start fresh and rebuild the documentation completely:

```bash
make clean
make html
```

### Viewing Your Changes

After building, your local documentation will be available at:

```
build/html/index.html
```

Open this file in any web browser to preview your changes before submitting.

### Making Changes

1. Create a new branch for your changes
   ```bash
   git checkout -b docs/your-feature-name
   ```

2. Make your documentation changes
3. Build and test locally
4. Commit your changes
   ```bash
   git add .
   git commit -m "Docs: Add information about XYZ feature"
   ```
5. Push to GitHub and create a Pull Request
   ```bash
   git push origin docs/your-feature-name
   ```


## Need Help?

If you encounter any issues with the documentation setup, please [open an issue](https://github.com/Aurora-Mission/Wiki/issues/new) or contact the project maintainers.
