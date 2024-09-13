# MeloTTS Setup with Virtual Environment

Follow these steps to set up MeloTTS with a virtual environment:

## 1. Create and Activate Virtual Environment

### On Windows:
```
python -m venv myenv
myenv\Scripts\activate
```
### On macOS/Linux:
```
python -m venv myenv
source myenv/bin/activate
```
## 2. Clone the MeloTTS Repository
```
git clone https://github.com/myshell-ai/MeloTTS.git
cd MeloTTS
```
## 3. Install MeloTTS in the Virtual Environment
```
pip install .
```
## 4. Download unidic
```
python -m unidic download
```
## 5. Deactivate the Virtual Environment (when you're done)
```
deactivate
```


