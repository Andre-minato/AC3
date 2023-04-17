rodando a aplicacao

pip install flask

docker image build -t python-web .

docker run -p 5050:5050 -d python-web
