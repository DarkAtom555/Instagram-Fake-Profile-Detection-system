UNDERSTANDING THE PROBLEM
This project aim is to build and train a deep neural network model to detect fake or spam instagram accounts.

These days spam accounts have become a major problem in in all the social media platforms.

Many users are creating fake accounts to create an illusion of having many followers to thier personal accounts.

Fake accounts are being created to sell fake products and services.

They are also being used to impersonate other account users from common people to celebrities in order to influence, criticize, hurt feelings and reputation.

There are few key input features which we considered to determine if the account is fake or not.

THE INPUT FEATURES ARE:

PROFILE PICTURE - The user has profile picture or not.
NUMS/LENGTH USERNAME - The ratio of number of numerical chars in username to its length.
FULLNAME WORDS - Full name in word tokens
NAME/LENGTH OF FULL NAME - The ratio of number of numerical characters in full name to its length.
NAME == USERNAME - Are username and full name literally the same?
DESCRIPTION LENGTH - Bio length in characters.
EXTERNAL URL - Has external URL or not.
PRIVATE - Private or not.
POSTS - Number of posts.
FOLLOWERS - Number of followers.
FOLLOWS - Number of follows.

TRAINED DETECTOR MODEL:*
This model is trained such that it considers the above given features and determines whether a particular account is fake or not. By resulting the output as either 0 or 1 meaning TRUSTED or FAKE respectively. Our intention is to make this software capable of thinking like a human, based on the data it is given and results in maximum probability of success.
