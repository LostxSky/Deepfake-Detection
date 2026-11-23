# Deepfake Detection

A deepfake detection project with a built web interface and Python-based components.

## Project Status

The repository currently contains the built frontend in `frontend/dist`. The Python backend source files and frontend development files need to be restored and committed before the complete detection application can be run from a fresh clone.

## Requirements

- Windows
- Git
- Python installed and available through the `py` launcher

## Clone the Repository

Open PowerShell and run:

```powershell
git clone https://github.com/LostxSky/Deepfake-Detection.git
cd Deepfake-Detection
```

## Preview the Built Frontend

The built frontend can be served as a static website. From the project root, run:

```powershell
cd frontend
..\ .venv\Scripts\python.exe -m http.server 8000 --bind 127.0.0.1 --directory dist
```

If using a fresh clone, create a Python environment first, or use an installed Python executable:

```powershell
py -m http.server 8000 --bind 127.0.0.1 --directory dist
```

Then open:

http://127.0.0.1:8000

Keep the terminal running while using the preview. Press `Ctrl+C` to stop the server.

> This serves only the built frontend. It does not start the Python backend or perform deepfake detection.

## Running the Complete Application

The complete application requires the backend source code, its dependency list, and any required model weights. Those files are not currently present in the checked project folder, so the backend startup command cannot be confirmed yet.

The frontend development server also requires the frontend source files and `package.json`, which are not currently present in the checked `frontend` folder.

Restore and commit those files before documenting the full setup commands.

## Project Credits

This repository is based on the original Deepfake Detector project:
Project setup, testing, and repository maintenance by Tanmay Jaswal ,Lesham Rai , Tansiq Sharma , Saptanshu .
Preserve any original license and attribution notices required by the project and its model dependencies.
