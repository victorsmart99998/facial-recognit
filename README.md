<p align="center">
  <p align="center">
    <a href="https://justdjango.com/?utm_source=github&utm_medium=logo" target="_blank">
      <img src="https://assets.justdjango.com/static/branding/logo.svg" alt="JustDjango" height="72">
    </a>
  </p>
  <p align="center">
    The Definitive Django Learning Platform.
  </p>
</p>

To learn how to build this application, [head over to our website.](https://justdjango.com)

This project is a facial recognition API. Users are able to create an account, utilise a free trial of the API, and create a membership to have full access to the API. Payments are handled with Stripe. The API is built with the Django Rest Framework and the frontend is built with React. The image recognition library is OpenCV. The project is deployed on Ubuntu using Digital Ocean.

## Backend development workflow

```json
virtualenv env
source env/bin/activate
pip install -r requirements.txt
python manage.py runserver
```

## Frontend development workflow

```json
npm i
npm start
```

## Deployment workflow
1. Change the manage.py to use the production settings
2. Change the constants.js file inside src to have DEBUG set to false
3. Push to the production environment
4. Run python manage.py migrate
5. Run npm run build
6. Run python manage.py collectstatic

## Disclaimer
This project does not cover concepts of image recognition - it is a proof of concept teaching how to take an idea from scratch to something real.

---

<div align="center">

<i>Other places you can find us:</i><br>

<a href="https://www.youtube.com/channel/UCRM1gWNTDx0SHIqUJygD-kQ" target="_blank"><img src="https://img.shields.io/badge/YouTube-%23E4405F.svg?&style=flat-square&logo=youtube&logoColor=white" alt="YouTube"></a>
<a href="https://www.twitter.com/justdjangocode" target="_blank"><img src="https://img.shields.io/badge/Twitter-%231877F2.svg?&style=flat-square&logo=twitter&logoColor=white" alt="Twitter"></a>

</div>
