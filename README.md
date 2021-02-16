# sass-demo-website

1. Variables - Create($textColor: white;) and use(color: $textColor;) variables.

2. Maps - Create($fontWeights: ("regular": 400 );) and use(font-weight: map-get($fontWeights, bold);) Maps

3. Partials are used when we dont want to make changes to the main.css files itself directly. We create another scss file with a prefix of '\_'. For ex. '\_reset.scss' and import it into our main.scss file

4. Functions are created where we return the get-map function and the associated value. Then we can use it by passing in a valid argument to get the associated value of the argument from the map.

5. Mixins are similar to functions but fnctions are used to compute values and mixins are used to define styles. If the argument passed in the mxin is false, it wont even appear on the css file.

6. @extend in scss is used in order to resuse the styles of another class with additional style modifications if you have any
