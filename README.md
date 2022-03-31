# ckanext-desq-theme

A custom theme for DESQ.


## Requirements

Tested with the following CKAN 2.9 fork:
https://github.com/whiskyechobravo/ckan/tree/desq-2.9.5


## Installation

1. Activate your CKAN virtualenv, for example:
   ```bash
   . /usr/lib/ckan/default/bin/activate
   ```

2. Install ckanext-desq-theme in the virtualenv:
   ```bash
   pip install -e 'git+https://github.com/whiskyechobravo/ckanext-desq-theme.git#egg=ckanext-desq_theme'
   ```

   **TODO:** Specify `[requirements]` if `requirements.txt` is not empty.

3. Add `desq_theme` to the `ckan.plugins` setting in your CKAN
   config file, e.g., `/etc/ckan/default/ckan.ini`.

4. Restart CKAN. Assuming it's installed as a systemd service:
   ```bash
   sudo service ckan restart
   ```


## License

[AGPL](https://www.gnu.org/licenses/agpl-3.0.en.html)
