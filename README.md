# wp-build - Thursday#
- Checkout new branch for Thursday, add, commit, and push
```sh
git checkout -b thursday
git add .
git commit -m "start of Thursday"
git push origin thursday
```
- Google Bootstrap CDN find the latest link to the min CSS file. Copy it to paste into the next step.
- In C9 editor open the theme ```functions.php``` file to the html5blank styles function, line 121
```sh
wp_enqueue_style('bootstrap', 'https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css'); 
```

- Open ```style.css``` in c9 editor and copy and paste all css from your local ```main.css``` file

- Open ```index.html``` in c9 editor and copy everything from after the header div to just before the footer div

- In WP open home page, switch to text view, paste everything you copied

- Open ```header.php``` in C9 and change class to ```container``` for the wrapper
- In ```header.php``` change ```<header>``` tag to ```<div>``` 
- In ```header.php``` update ```class="header clear"``` to ```class="header clearfix"```
- In ```header.php``` remove ```role="banner"```
- Open ```page.php``` and //comment out side bar (at the bottom) and comments and edit post link (middle)
- Remove the h1 stuff from ```page.php``` and paste into ```header.php```
- Remove ```<nav>``` ```class``` and ```role``` from ```page.php```
- Update ```'menu_class' => 'nav nav-pills float-right'```, in ```functions.php``` (should be line 75)