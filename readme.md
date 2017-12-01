#Google Cloud Contekan
```
gcloud auth login

gcloud auth list
gcloud config set account  aulia.sintha88@gmail.com

gcloud projects create dewi-inten
gcloud projects list
gcloud config set project dewi-inten

gcloud app regions list
gcloud app create --region asia-northeast1 --project dewi-inten

git clone https://github.com/kopetgroup/gcloud-php-starter.git .

gcloud app deploy public/app.yaml --quiet --project dewi-inten
gcloud app browse
```
