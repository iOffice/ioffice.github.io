# iOffice API Documentation

## Making edits to the API documentation
To make edits to the API documentation you will need to install
[aglio].

	npm install -g aglio

You will need to modify the appropriate `md` file, e.g. maintenance.md, in order 
to update the endpoint you have modified. You can then view your changes before
updating the index.html file following the steps below.

## Viewing changes locally
To see the changes made to the API call the make file by running
the `make` command. This will execute the following:

	aglio -i api.md -t flatly --full-width -s

This will start **localhost:3000** so that you can view your changes *only*.

## Updating the index.html 
To export the changes run the `make export` command. This will execute the following:

	aglio -i api.md -t flatly --full-width -o index.html

You can alternatively execute the command yourself. It is **required** that you run `make export` or the script above to update the 
`index.html` file in order for your changes to appear in master.

For more info on the syntax used see the [API Blueprint][1] documentation.

[1]: https://github.com/apiaryio/api-blueprint/blob/master/API%20Blueprint%20Specification.md
[aglio]: https://github.com/danielgtaylor/aglio
