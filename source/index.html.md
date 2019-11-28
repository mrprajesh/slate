---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ


toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# Introduction

Welcome to the Kittn API! You can use our API to access Kittn API endpoints, which can get information on various cats, kittens, and breeds in our database.

We have language bindings in Shell, Ruby, Python, and JavaScript! You can view code examples in the dark area to the right, and you can switch the programming language of the examples with the tabs in the top right.

This example API documentation page was created with [Slate](https://github.com/lord/slate). Feel free to edit it and use it as a base for your own API's documentation.

# Authentication

## Sample Section
This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. 

This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. This is text in Section. 

# Kittens

## Get All Kittens


We don't need this.

This endpoint retrieves all kittens.

### HTTP Request

`GET http://example.com/api/kittens`

### Query Parameters

Parameter | Default | Description
--------- | ------- | -----------
include_cats | false | If set to true, the result will also include cats.
available | true | If set to false, the result will include kittens that have already been adopted.

<aside class="success">
Remember — a happy kitten is an authenticated kitten!
</aside>

## Get a Specific Kitten

 
This endpoint retrieves a specific kitten.

<aside class="warning">Inside HTML code blocks like this one, you can't use Markdown, so use <code>&lt;code&gt;</code> blocks to denote code.</aside>

### HTTP Request

`GET http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to retrieve

## Delete a Specific Kitten
 

This endpoint deletes a specific kitten.

### HTTP Request

`DELETE http://example.com/kittens/<ID>`

### URL Parameters

Parameter | Description
--------- | -----------
ID | The ID of the kitten to delete

