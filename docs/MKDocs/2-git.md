# Git einrichten

Bevor hiermit gestartet werden kann, muss erst die Installation abgearbeitet sein.

=== "Ubuntu"

    Venv aktivieren
    ```
    source venv/bin/activate
    ```

    Email und Name setzen
    ```
    git config --global user.email "<email>"
    ```

    ```
    git config --global user.name "<name>"
    ```

    Repo url ändern
    ```
    git remote set-url origin https://<git-name>:<Access-Token@github.com/<git-name>/<repo>.git
    ```

=== "Windows"
