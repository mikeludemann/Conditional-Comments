# Conditional Comments

A tutorial for conditional comments

```code

If not Internet Explorer with version 6

<!--[if !IE 6]>
    <link rel="stylesheet" type="text/css" href="styles.css" />
<![endif]-->

If smaller as Internet Explorer with version 7

<!--[if lt IE 7]>
    <link rel="stylesheet" type="text/css" href="styles.css" />
<![endif]-->

If smaller as or equal Internet Explorer with version 8

<!--[if lte IE 8]>
    <link rel="stylesheet" type="text/css" href="styles.css" />
<![endif]-->

If greater as Internet Explorer with version 7

<!--[if gt IE 7]>
    <link rel="stylesheet" type="text/css" href="styles.css" />
<![endif]-->

If greater as or equal Internet Explorer with version 8

<!--[if gte IE 8]>
    <link rel="stylesheet" type="text/css" href="styles.css" />
<![endif]-->

If Internet Explorer with version 9

<!--[if IE 9]>
    <link rel="stylesheet" type="text/css" href="styles.css" />
<![endif]-->

If Internet Explorer with version 8 or 9

<!--[if (IE 8) | (IE 9)]>
    <link rel="stylesheet" type="text/css" href="styles.css" />
<![endif]-->

If Internet Explorer with version 8 and 9

<!--[if (IE 8) & (IE 9)]>
    <link rel="stylesheet" type="text/css" href="styles.css" />
<![endif]-->

```