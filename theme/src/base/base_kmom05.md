@import "../@desinax/typographic-grid/less/typography-sizes.less";
/**
 * Base style to affect HTML elements on a general scale.
 */
@bgColorHtml: #424242;
@bgColorBody: #fff;
@colorBody: #333;
//@fontFamilyBody: serif;
@magicNumber:   24px; /* 16px - 100%/1.5 */
//@magicNumber:   22px; /* 16px - 100%/1.375 */
@fontSizeBody:  16px;
@lineHeight:    (unit(@magicNumber) / unit(@fontSizeBody));

@fontSizeH1: 2.375em;


html {
    overflow-y: scroll;
    background-color: @bgColorHtml;
    font-size: 100%;

}

body {
    margin: 0 auto;
    padding: 0;
    color: @colorBody;
    background-color: @bgColorBody;
    //font: 100.01%/1 @fontFamilyBody;
    #desinax-hgrid.font(@fontSizeBody);
    line-height: @lineHeight;
}

p {
    font-size: 1em;
    margin-bottom: @magicNumber;
    line-height: @lineHeight;
    font-family: 'Raleway', sans-serif;
}

h1 {
    font-size: @fontSizeH1;
    margin-bottom: @magicNumber;
//    line-height: @lineHeight;
    font-family: 'Changa', sans-serif;
}

@media screen and (min-width: 912px) {

    .blog-list-item h1 {
        clear: both;
    }
}
// Activate grid and affect all typographic elements
#desinax-hgrid.activateDefaultTypography();
