/* Grid vertical for kmom03 */

/**
 * Import the vertical grid.
 */
@import "../src/@desinax/vertical-grid/less/grid.less";
@import "../@desinax/typographic-grid/less/typography-font-families.less";
@import "../@desinax/typographic-grid/less/typography-sizes.less";


/* Font from Google */
@import url('https://fonts.googleapis.com/css?family=Changa:200');
@import url('https://fonts.googleapis.com/css?family=Changa:200|Raleway:300|Source+Code+Pro:200');

.row {
    #desinax-vgrid.row();
    background-color: #0f0;
    //padding-top: 8px;
    //padding-bottom: 8px;
    background-color: transparent;
}

.region {
    height: 80px;
    background-color: lighten(#0f0, 20%);
    // Add some style to make it easier to see the structure of the grid
    opacity: 0.5;
}

.inner-wrap-main {
    #desinax-vgrid.grid(1100px);
}

.inner-wrap-header,
.inner-wrap-footer {
    #desinax-vgrid.grid(100%);
}

.breadcrumb-list {
    #desinax-vgrid.column(@columns - 4);
    #desinax-vgrid.push(1);

}
//Header Nav bar ------------------------------
.site-logo-text a {
    font-family: 'Changa', sans-serif;
    font-size: 2em;
    text-decoration: none;
    color: #333;
}

.region-header-col-1 {
    #desinax-vgrid.column(@columns - 20);
}

.region-header-col-3 {
    #desinax-vgrid.column(@columns - 22);
}

.region-header-col-2 {
    #desinax-vgrid.column(@columns - 8);
}

.inner-wrap-flash {
    #desinax-vgrid.column(@columns - 4);
    #desinax-vgrid.push(2);

}

 .region-flash img {
     #desinax-vgrid.column(@columns);
}


// Main ---------------------------

.region-main {
     #desinax-vgrid.column(@columns - 2);
}

.article img {
     #desinax-vgrid.column(@columns);
 }

//video
.figure iframe {
    #desinax-vgrid.column(@columns);
}

.figure.asciinema {
    #desinax-vgrid.column(@columns);
}
//ascii
.figure.asciinema script {
    #desinax-vgrid.column(@columns);
}

.sidebar-left,
.sidebar-right {
    #desinax-vgrid.column(@columns / 4);
}

.vgrid .inner-wrap {
    @gridImage: "../img/grid_24x30x10-nomargin.png";
    //@gridImage: "../../img/grid_12x60x20-nomargin.png";
    #desinax-vgrid.showGrid(@gridImage, 1100px);

    &.inner-wrap-header,
    &.inner-wrap-footer {
        #desinax-vgrid.showGrid(@gridImage);
    }
}

.stylechooser {
    margin-bottom: @magicNumber;
}
.stylechooser select {
    #desinax-vgrid.column(@columns - 4);
}

.figure.right img {
    float: right;
    padding: .5em;
    width: 15em;
}

/* Header -------------------------------------- */
.site-logo img {
  display: none;
}

/* Navbar -------------------------------------- */
.rm-navbar {
    display: block;
    }

    li {
        display: inline-block;
        background-color: white;
    }

    a {
        text-decoration: none;
        font-family: 'Changa', sans-serif;
        font-size: 1.1em;
    }

.rm-desktop {
    li ul {
        display: none;
        position: absolute;
        z-index: 1;
    }

    li:hover ul {
        display: block;
    }

    li ul li {
        display: block;
    }
}

#rm-menu li {
    background-color: black;
    color: white;
    font-size: 1.4em;
}

/* About -------------------------------------- */

.region-main.has-sidebar-right {
    #desinax-vgrid.column(@columns - 10);
    #desinax-vgrid.push(2);
}


.wrap-sidebar.region-sidebar-right {
    #desinax-vgrid.column(@columns - 19);
    #desinax-vgrid.push(1);
}



.figure.design-photo img {
    #desinax-vgrid.column(@columns);
    width: 30em;
}



/* Redovisning / OM / VERKTYG--------------------------------- */
.region-main.has-sidebar-left {
    #desinax-vgrid.column(@columns - 10);
    #desinax-vgrid.push(1);
}

.wrap-sidebar {
    #desinax-vgrid.column(@columns - 19);
    #desinax-vgrid.push(1);
}

.block {
    margin-bottom: @magicNumber * 2;
}

.toc ul li {
    display: block;
}


/* Blog --------------------------*/
.figure.kiwi {
    float: right;
    clear: both;
    padding: .3em;
}


// Next previous buttons ----------------
.next-previous {
    #desinax-vgrid.column(@columns);
    margin-bottom: @magicNumber;
}

.next {
    float: right;
}

.previous {
    float: left;
}

// Menu element on Verktyg
.block {
    .section-header {
        font-size: 1.5em;
        text-decoration: none;
    //    padding: 5px;
    }
    a {
        text-decoration: none;
    }
    ul {
        list-style-type: none;
    }
}


/* Byline -------------------------------------- */

.figure.left img {
    float: left;
    padding: 10px;
}

.author-byline {
    #desinax-vgrid.column(@columns - 20);
}

.author-byline p {
    padding-top: 30px;
    width: 40em;
}
/* Footer -------------------------------------- */

.inner-wrap-footer {
    #desinax-vgrid.column(@columns - 2);
    #desinax-vgrid.push(1);
}

.footer-column {
    #desinax-vgrid.column(@columns / 3);
    p,
    h4 {
        color: #fff;
    }
}
//codyright
.site-footer {
    #desinax-vgrid.column(@columns / 1);

    p {
        color: #fff;
    }
    //#desinax-vgrid.push(1);
}

.region-footer h4 {
  font-size: 2em;
}
