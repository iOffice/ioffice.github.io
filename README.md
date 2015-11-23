# iOffice

To make edits to the API documentation you will need to install
[aglio].

	sudo npm install -g aglio

To see the changes made to the API call the make file by running
the `make` command. This will execute the following:

	aglio -i api.md -t flatly --full-width -s

To export the changes run `make export` or

	aglio -i api.md -t flatly --full-width -o index.html

For more info on the syntax used see the [API Blueprint][1] documentation.

[1]: https://github.com/apiaryio/api-blueprint/blob/master/API%20Blueprint%20Specification.md
[aglio]: https://github.com/danielgtaylor/aglio
