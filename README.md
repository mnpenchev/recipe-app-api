API for a cooking recipes site with following features: Create and update user profile, Create recipes with description and picture, Login and authentication, Posting status updates, viewing profiles and updates.


Installation

Pull the repo and run: docker-compose build

Start/Stop the server: docker-compose up/down

Run the tests: docker-compose run --rm app sh -c "python manage.py test"

Authentication requires token, when a new user is registered ot logged an Auth token is created. It can be easily simulated with Chrome extention ModHeader: https://chrome.google.com/webstore/detail/modheader/idgpnmonknjnojddfkpgkljpfnnfcklj?hl
