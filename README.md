# Web-Scrapping-of-flipkart-using-Python

1). Heroku Deployment

- First install Heroku cli as per your system compatibility: https://devcenter.heroku.com/articles/heroku-cli
- Create a heroku account.
- Will push our project in github.
- Create a new repository in github.Open you cmd, be in your project folder first then run the below commands:
      - git init
      - git add .
      - git commit -m "first commit"
      - git branch -M main
      - git remote add origin 'your own .git' file(like this git remote add origin https://github.com/vikash130795/era.git)
      - git push -u origin main
      
- Check in your cmd heroku is installed or not by this command, 'heroku'.
- If its available then, do login in heroku using this command 'heroku login'.
- Be in your project folder and run this command 'heroku git:remote -a <your appname>'
- Then, push your code with this command 'git push heroku master'
- Now, your app is successfully deployed in heroku.     
