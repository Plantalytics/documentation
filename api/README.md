# Compiling documentation to HTML #
You may use raml2html or raml-fleece though I prefer raml-fleece.

## raml-fleece ##
1. `npm install -g raml-fleece`
2. `raml-fleece plantalytics.raml > plantalytics.html`

## raml2html ##
1. `npm install -g raml2html`
2. `raml2html -i plantalytics.raml -o plantalytics.html`

# Using in Postman #
1. In Postman in the upper left click the **Import** button.
2. Select the **Import Folder** tab.
3. Select this folder, *api*
4. If the left pane is not open, you can open it from the upper-left-most button.
5. Select the **Collections** tab and you will see *Plantalytics API*
