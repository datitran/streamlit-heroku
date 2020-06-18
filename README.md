# Streamlit + Heroku Hello World Example

1. Login into Heroku:
```
heroku login
```

2. Create Heroku instance:
```
heroku create 
```

3. Push the app:
```
git push heroku master
```

4. Run the app:
```
heroku ps:scale web=1
heroku open
```