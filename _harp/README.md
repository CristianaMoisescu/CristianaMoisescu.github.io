Cristiana.Moisescu.com
======================

The website uses HARPjs. Install it on your sistem to do development.

Important file: '_harp/harp.json'

Run local server:

* open terminal
* `harp server --port 8080 _harp`

On c9.io click on 'Preview'. If you run it locally, go to the address displayed in the terminal.

(optional) Review changes: `git diff` (Q to exit)

To deploy:

1. Regenerate static html: `harp compile _harp ./`
2. Add all the files to the repository: `git add --all .`
3. Commit the changes to the repo `git commit -m 'Update site'` (Replace 'Update site' with what you actually did -- e.g. _Update bio with my new prize_)
4. Push the changes to the server: `git push`
5. Enjoy your updated site