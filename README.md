# shoutouts.lol embed shortcode

Adds your shoutouts.lol embed script tag using the Hugo shortcode `{{< shoutouts >}}` within your content.

To embed it into your template files, for example into the footer, you can import the shoutouts embed partial using `{{ partial "shoutouts/embed.html" . }}`. If you want to pass in a custom theme, you can do so by passing in the `theme` parameter, for example `{{ partial "shoutouts/embed.html" (dict "context" . "theme" "38") }}`.
