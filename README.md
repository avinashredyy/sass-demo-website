# sass-demo-website

1. Variables - Create($textColor: white;) and use(color: $textColor;) variables.

2. Maps - Create($fontWeights: ("regular": 400 );) and use(font-weight: map-get($fontWeights, bold);) Maps

3. Partials are used when we dont want to make changes to the main.css files itself directly. We create another scss file with a prefix of '\_'. For ex. '\_reset.scss' and import it into our main.scss file.
