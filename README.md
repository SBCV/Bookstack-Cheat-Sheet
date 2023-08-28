# Bookstack-Configuration

Use [Custom HTML Head Content](https://www.bookstackapp.com/docs/admin/hacking-bookstack/#custom-html-head-option) to modify the appearance of bookstack.

> Within the “Settings > Customization” view within BookStack you’ll find a “Custom HTML Head Content” setting. You can use this to add in any custom JavaScript or CSS content which enables you to override default BookStack functionality and styles.
> 
> You can find examples of custom HTML Head customizations on the [hacks part of this site](https://www.bookstackapp.com/hacks/).

## [Change Fontsize](https://github.com/BookStackApp/BookStack/issues/462) (applies to html and pdf exports)
```
<style>
.page-content h1 { font-size: 2rem; }
.page-content h2 { font-size: 1.8rem; }
.page-content h3 { font-size: 1.6rem; }
.page-content h4 { font-size: 1.4rem; }
.page-content h5 { font-size: 1.3rem; }
.page-content h6 { font-size: 1.15rem; }
</style>
```

## [Change Color](https://github.com/BookStackApp/BookStack/issues/1380) (does NOT apply to the html and pdf exports)
```
<style>
	:root {
		--color-page: #a242d7;
		--color-page-draft: #cfb732;
		--color-chapter: #db5382;
		--color-book: #534ecb;
		--color-bookshelf: #3eeaf0;
	}
</style>
```
