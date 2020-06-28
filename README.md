
# Ruby on Rails Server Using Amazon EC2 with Pulumi


    ```bash
    $ pulumi up
    ```


    ```bash
    $ pulumi stack output
    ```

    ```bash
    $ curl $(pulumi stack output websiteURL)
    ```
    
    ```bash
    $ pulumi destroy --yes
    $ pulumi stack rm --yes
    ```

# Github Actions

Any PR we do will call
    ```bash
    $ pulumi preview
    ```

Any commit we make in master will call

    ```bash
    $ pulumi up
    ```
