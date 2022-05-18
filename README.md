
# SMS Spam Detector

I've created this `sms_spam_classifier` app on Heroku which can identify an sms as ham or spam.

I've experimented this with different classifier models and got to know that multinomial Naive_bayes is out performing the rest. Hence NB model is used in deploying this app.

**Libraries used:**
- pandas
- streamlit
- nltk

This system is created with `tfidf` algorithm in Natural Language Processing.

I've used stemming method to get the root words.

If you've any questions related to Heroku deployment, you can check the Heroku documentation page.

Heroku App Link: https://sms-spam-classifier-vkp.herokuapp.com/

