# Online Marketplace

Online Marketplace created with the Django framework
Contains the following faetures:

- Authentication [Built-in Django functionality to handle users]
- Communication between users [A user can contact the seller of a product]
- Dashboard for your items [Items can be added, edited and deleted by a logged-in user]

### Status

Due for upgrades

### Usage

In order to download this code, either click the green button at the top right and download as ZIP, or clone the repository. Enter the repository directory. You will need to `pip install -r requirements.txt` (or use `pip3` if you are getting a module not found error).

In the folder, you will find these sub-folders:

- puddle: master folder for the app. Contains `setting.py` and `urls.py` as config files.
- core: homepage/signup/login templates and related urls. User can sign-up, login and logout from their account.
- dashboard: displays the items that were created by the current authenticated user [will be removed later]
- item: contains details about items and their categories. A user can filter the items based on category as well as search for items.
- conversation: handles conversation between a logged-in user and seller(s)

Run the following in your terminal.

```
python3 manage.py runserver
```

### Notes

- Add an "add to cart" function
- Adjust the precision of floating-point fields so that 250.0 is displayed as 250.00
- Display currency symbol
- Integrate a payment gateway API so that users are able to checkout and pay for the items

### Credits

- [Learn Django by Building an Online Marketplace – Python Tutorial for Beginners](https://www.youtube.com/watch?v=ZxMB6Njs3ck) by freeCodeCamp ([CodeWithStein](https://www.youtube.com/c/CodeWithStein))
- [Deployment to Railway](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Deployment)
