---
layout: page
permalink: doc_clan_store.html
show_in_menu: False
title: Documentation Clan Store Service
---

# REST API

<link rel="stylesheet" type="text/css" href="swagger_res/swagger-ui.css" />
<script src="swagger_res/swagger-ui-bundle.js" charset="UTF-8"> </script>
<script src="swagger_res/swagger-ui-standalone-preset.js" charset="UTF-8"> </script>
<script>
  window.onload = function() {
    window.ui = SwaggerUIBundle({
      url: "openapi_files/ms_clan_store.json",
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
