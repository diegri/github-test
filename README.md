# github-test
python app.py

# Test actions form locals
act --workflows ".github/workflows/python-app.yml" --job "build" --secret-file "" --var-file "" --input-file "" --eventpath ""


# Docker build and run
docker image build -t testweb .
docker run -p 5000:5000 -d testweb

# Verificar antiguedad librerias
libyear text requirements.txt

