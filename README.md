# fund.liberland.org deployment

## Development

Start your own local instance

    vargrant up

## Production

Run ansible playbook against production server

    ansible-playbook --private-key=~/.ssh/liberland_rsa -i inventory.txt playbook.yml

Run application deployment

    bundle exec cap production deploy
