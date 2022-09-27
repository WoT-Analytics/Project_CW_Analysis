---
layout: page
permalink: doc_clan_api.html
show_in_menu: False
title: Doc ms_clan_api
---

# MS_CLAN_API

<link rel="stylesheet" type="text/css" href="swagger_res/swagger-ui.css" />
<script src="swagger_res/swagger-ui-bundle.js" charset="UTF-8"> </script>
<script src="swagger_res/swagger-ui-standalone-preset.js" charset="UTF-8"> </script>
<script>
  window.onload = function() {
    window.ui = SwaggerUIBundle({
      url: "openapi_files/ms_clan_api.json",
      dom_id: '#swagger-ui',
      deepLinking: true,
      supportedSubmitMethods: [],
      presets: [
        SwaggerUIBundle.presets.apis
      ],
      plugins: [
        SwaggerUIBundle.plugins.DownloadUrl
      ]});
  };
</script>

<div style="background-color: #fff;padding: 25px">
    <div id="swagger-ui"></div>
</div>
