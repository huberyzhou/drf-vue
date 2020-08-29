Open terminal and run:

```shell
virtualenv -p python3 venv
# or in local
conda activate django

source venv/bin/activate
git clone https://github.com/sinisaos/drf-vue.git

cd drf-vue/backend/
sudo -H pip install -r requirements.txt

python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
如果出现Restful API就是成功了
然后去前端 cd ../frontend

