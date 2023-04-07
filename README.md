# shoutouts.lol embed on Micro.blog

![shoutouts.lol embed on Micro.blog](https://github.com/vincentritter/plugin-shoutouts-on-mb/raw/main/docs/shoutout-embed-in-footer.jpg)

Adds your shoutouts.lol embed script tag using the Hugo shortcode `{{< shoutouts >}}` within your content. If you want to pass in a custom theme, you can do so by passing in the `theme` parameter, for example `{{< shoutouts theme="38" >}}`.

To embed it into your template files, for example into the footer, you can import the shoutouts embed partial using `{{ partial "shoutouts/embed.html" . }}`.

If you want to pass in a custom theme, you can do so by passing in the `theme` parameter, for example `{{ partial "shoutouts/embed.html" (dict "context" . "theme" "38") }}`.

## shoutouts.lol

You need to have a shoutouts.lol account to use this plugin. If you don't have one yet, you can create one here: [shoutouts.lol](https://shoutouts.lol).

Once registered you can find your embed code at the top of the embed page: [shoutouts.lol/embed](https://shoutouts.lol/embed).

To create extra themes, head on over to the theme section: [shoutouts.lol/themes](https://shoutouts.lol/themes).

## Extras

This plugin was created by [me](https://vincentritter.com)  and you can you can see it in use on my social page: [social.vincentritter.com](https://social.vincentritter.com).