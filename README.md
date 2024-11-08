# Shoutouts embed on Micro.blog

![Shoutouts.page embed on Micro.blog](https://github.com/vincentritter/plugin-shoutouts-on-mb/raw/main/docs/shoutout-embed-in-footer.jpg)

## Shortcodes
Adds your shoutouts.page embed script tag using the Hugo shortcode `{{< shoutouts >}}` within your content. If you want to pass in a custom theme, you can do so by passing in the `theme` parameter, for example `{{< shoutouts theme="38" >}}`.

There is also the option to bring back just one specific shoutout, for example `{{< shoutouts theme="38" shoutout="34" >}}`. This is useful if you want to highlight a specific shoutout. You can omit the `theme` parameter if you want to use the default theme.

## Partials
To embed it into your template files, for example into the footer, you can import the shoutouts embed partial using `{{ partial "shoutouts/embed.html" (dict "context" . ) }}`.

If you want to pass in a custom theme, you can do so by passing in the `theme` parameter, for example `{{ partial "shoutouts/embed.html" (dict "context" . "theme" "38") }}`.

There is also the option to bring back just one specific shoutout, for example `{{ partial "shoutouts/embed.html" (dict "context" . "theme" "38" "shoutout" "34") }}`. This is useful if you want to highlight a specific shoutout. You can omit the `theme` parameter if you want to use the default theme.

## Shoutouts.page

You need to have a shoutouts.page account to use this plugin. If you don't have one yet, you can create one here: [Shoutouts.page](https://shoutouts.page).

Once registered you can find your embed code at the top of the embed page: [shoutouts.page/embed](https://shoutouts.page/embed).

To create extra themes, head on over to the theme section: [shoutouts.page/themes](https://shoutouts.page/themes).

## Extras

This plugin was created by [me](https://vincentritter.com).
