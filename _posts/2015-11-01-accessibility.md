---
title: Accessibility 
subtitle: An exercise in using cookies and user options to store display information from a widget. 
---
## PHP

### Functions
[setcookie()](https://secure.php.net/manual/en/function.setcookie.php)

## WordPress

### Functions
[wp_send_json()](https://codex.wordpress.org/Function_Reference/wp_send_json)
[wp_send_json_success()](https://codex.wordpress.org/Function_Reference/wp_send_json_success)
[wp_send_json_error()](https://codex.wordpress.org/Function_Reference/wp_send_json_error)

### Actions
[wp_ajax_(action)](https://codex.wordpress.org/Plugin_API/Action_Reference/wp_ajax_(action))


## JavaScript
[jQuery.ajax()](https://api.jquery.com/jquery.ajax/)

## Best Practices
[WordPress Widgets](https://codex.wordpress.org/WordPress_Widgets)
[Validating Sanitizing and Escaping User Data](https://codex.wordpress.org/Validating_Sanitizing_and_Escaping_User_Data)
[AJAX in Plugins](https://codex.wordpress.org/AJAX_in_Plugins)
[WordPress Nonces](https://codex.wordpress.org/WordPress_Nonces)

## Assignment
Create a plugin for a Widget that allows site visitors to adjust the colors and font size of your site. Store these preferences in a cookie for unlogged-in visitors, and in a user option for logged-in users. Use AJAX to communicate between the front-end Widget and WordPress to save the option or cookie. You can instruct the user to reload the page for their changes to take effect -- bonus points if they don't have to reload (this will involve more JavaScript).

- What information do you need to store in order to change the site's CSS?
- What are acceptable values for this information?

## Additional reading
