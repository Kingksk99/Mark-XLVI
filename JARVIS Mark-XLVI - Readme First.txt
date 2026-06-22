git clone https://github.com/FatihMakes/Mark-XLVI.git
cd Mark-XLVI
pip install -r requirements.txt
playwright install
pip install google-genai
winget install Python.Python.3.12 && winget install Python.Python.3.11
py -3.12 -m pip install sounddevice
pip install PyQt6
python main.py


Add this path into the system environment variables
C:\Users\KSK\AppData\Roaming\Python\Python314\Scripts