$ rails new solidusZero --database=postgresql
$ touch Starter.md Source.md
rails db:create
bundle add solidus
rails g solidus:install
    - starter
    - stripe
    <!-- paypal | braintree -->
<!-- Creating admin user with:
- email: admin@example.com
- password: test123 -->
<!-- "Solidus has been installed successfully. Enjoy!" -->


