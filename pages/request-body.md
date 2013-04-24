---
title: Request Body
layout: default
---

Use the request object's `getBody()` method to fetch the raw HTTP request body sent by the HTTP client. This is
particularly useful for Slim applications that consume JSON or XML requests.

    <?php
    $request = $app->request();
    $body = $request->getBody();
