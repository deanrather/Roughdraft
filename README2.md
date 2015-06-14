Go to Heroku.com, and create an account

Note your email and password

	deanrather@gmail.com
	df23r2fsdEFS

Fork the RoughDraft Repo to your own GitHub Accounot

Clone the RoughDraft Repo to your Dev Machine

	git clone git@github.com:deanrather/Roughdraft.git

Install the Heroku Toolbelt

	wget -qO- https://toolbelt.heroku.com/install-ubuntu.sh | sh

Create the Heroku Server

    heroku login
    heroku create
    heroku addons:create redistogo
    ... whelp. It requires a "verified" account, which required credit card details. Nope.
    