# Css Translate Middle for Bootstrap v5 installed with CDN

Useful if you use [Bootstrap v5 CDN](https://getbootstrap.com/docs/5.2/getting-started/introduction/#cdn-links) and don't use Sass files in your project. 

In [Bootstrap 5 Docs](https://getbootstrap.com/docs/5.3/utilities/position/) you can find that translate middle classes are not set with responsive utility classes.
If you need ***pure CSS*** classes you can use this repo and add these classes in your bootstrap.css file.

You can just integrate these classes in the bootstrap.min.css file or copy them in your own style.css.

An example of utility:

```css

@media (min-width: 576px) {

    .translate-middle-sm {
        -webkit-transform: translate(-50%, -50%) !important;
        -moz-transform: translate(-50%, -50%) !important;
        -ms-transform: translate(-50%, -50%) !important;
        -o-transform: translate(-50%, -50%) !important;
        transform: translate(-50%, -50%) !important;
    }

    .translate-middle-sm-x {
        -webkit-transform: translateX(-50%) !important;
        -moz-transform: translateX(-50%) !important;
        -ms-transform: translateX(-50%) !important;
        -o-transform: translateX(-50%) !important;
        transform: translateX(-50%) !important;
    }

    .translate-middle-sm-y {
        -webkit-transform: translateY(-50%) !important;
        -moz-transform: translateY(-50%) !important;
        -ms-transform: translateY(-50%) !important;
        -o-transform: translateY(-50%) !important;
        transform: translateY(-50%) !important;
    }

}

```

Hope it can help! :gift: :sos: :blush:
