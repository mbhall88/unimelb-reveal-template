This repository is designed to be used as a template for people wanting to create a University of Melbourne-themed 
[reveal.js][reveal] slide deck. It is **not** an official University of Melbourne project, but it does adhere to the [typography] 
and [colour palette][palette] guidelines of the university.

## Getting started
1. 👀 [View the demo presentation][demo]
2. 📚 [Read the reveal.js documentation](https://revealjs.com/markup/)
3. 🚀 [Install](#install)
4. 💅 [Customise](#customise)
5. 🍽️ [Serve](#serve)


## Install

1. Install [Node.js][node]
2. Click [**Use this template**](https://github.com/mbhall88/unimelb-reveal-template/generate) and follow the prompts to create a repository for your slide deck
3. Clone your new repository locally
4. From inside the project root directory, run `npm install`
5. Serve the slides locally with `npm start` and navigate to <http://localhost:8000/> in your browser. This will reload the presentation anytime you make a change to it
6. Make your slides!

## Customise

For customisation topics not addressed below, please first check the [reveal.js documentation][reveal-docs]. If your question is not 
covered there, then [raise an issue](https://github.com/mbhall88/unimelb-reveal-template/issues).

### Colours

The entire [UoM colour palette][palette] is located in the theme SCSS file `css/theme/source/uom.scss`. Use those 
variables to change the colours of any element in the slides by altering the fields in that theme SCSS file, or adding 
any new ones.

### Logo

All slides have a UoM logo in the bottom left corner. If you want to add additional logos, an example can be found 
in `index.html` - in the commented logos section. You will see an `<img>` tag that has been commented out 
which provides a [Doherty Institute][doherty] logo. If you're at the Doherty Institute, then simply uncomment the 
line. If you want to add a logo for another entity/organisation, you can copy the same process as was used for the 
UoM and Doherty Institute logos.

To change the position of the logos, navigate to the theme SCSS file `css/theme/source/uom.scss` (find the logo 
positioning section). Change the `bottom`, `left` etc. fields to place your logo where you want - or change its size.

### Border

You can change the width and colour of the border(s) in `css/theme/source/uom.scss`. By default, this template has 
a top and bottom border in UoM blue. To add/remove borders, (un)comment the relevant `<div>` tags in the border section in `index.html`.

## Serve

By default, the main branch of the template is `gh-pages`, as such, your slides should be automagically served. On the 
GitHub repository, navigate to **Settings>Pages** and you should see a section saying "Your site is live at ....". 
Whenever you push to the repository, the live slides should update in a minute or two.

[reveal]: https://github.com/hakimel/reveal.js/
[reveal-docs]: https://revealjs.com/
[palette]: https://brandhub.unimelb.edu.au/guidelines/colour-palette
[typography]: https://brandhub.unimelb.edu.au/guidelines/typography
[demo]: https://mbh.sh/unimelb-reveal-template
[node]: https://nodejs.org/en/
[doherty]: https://www.doherty.edu.au/