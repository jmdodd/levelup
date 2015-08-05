---
title: The seven dirty words
subtitle: An introduction to WordPress plugins, filters, and regular expressions.
---
## PHP

### Data types
[https://secure.php.net/manual/en/language.types.php](https://secure.php.net/manual/en/language.types.php)
[https://secure.php.net/manual/en/language.types.string.php](https://secure.php.net/manual/en/language.types.string.php)
[https://secure.php.net/manual/en/language.types.array.php](https://secure.php.net/manual/en/language.types.array.php)

### Control structures
[https://secure.php.net/manual/en/language.control-structures.php](https://secure.php.net/manual/en/language.control-structures.php)
[https://secure.php.net/manual/en/control-structures.if.php](https://secure.php.net/manual/en/control-structures.if.php)
[https://secure.php.net/manual/en/control-structures.foreach.php](https://secure.php.net/manual/en/control-structures.foreach.php)
[https://secure.php.net/manual/en/control-structures.continue.php](https://secure.php.net/manual/en/control-structures.continue.php)

### Strings
[https://secure.php.net/manual/en/book.strings.php](https://secure.php.net/manual/en/book.strings.php)
[https://secure.php.net/explode](https://secure.php.net/explode)
[https://secure.php.net/strpos](https://secure.php.net/strpos)
[https://secure.php.net/stripos](https://secure.php.net/stripos)
[https://secure.php.net/substr](https://secure.php.net/substr)

### Regular expressions (Perl-compatible)
[https://secure.php.net/manual/en/book.pcre.php](https://secure.php.net/manual/en/book.pcre.php)
[https://secure.php.net/preg-match](https://secure.php.net/preg-match)
[https://secure.php.net/preg-replace](https://secure.php.net/preg-replace)

## WordPress

### Coding standards
[https://make.wordpress.org/core/handbook/coding-standards/php/](https://make.wordpress.org/core/handbook/coding-standards/php/)

### Debugging
[https://codex.wordpress.org/Debugging_in_WordPress](https://codex.wordpress.org/Debugging_in_WordPress)

### Plugins
[https://codex.wordpress.org/Writing_a_Plugin](https://codex.wordpress.org/Writing_a_Plugin)

### Filters
[https://codex.wordpress.org/Plugin_API#Filters](https://codex.wordpress.org/Plugin_API#Filters)
[https://codex.wordpress.org/Function_Reference/add_filter](https://codex.wordpress.org/Function_Reference/add_filter)
[https://codex.wordpress.org/Function_Reference/comment_text](https://codex.wordpress.org/Function_Reference/comment_text)
[https://core.trac.wordpress.org/browser/tags/4.2.2/src/wp-includes/comment-template.php#L827](https://core.trac.wordpress.org/browser/tags/4.2.2/src/wp-includes/comment-template.php#L827)

## Regular expressions
[http://www.regular-expressions.info/quickstart.html](http://www.regular-expressions.info/quickstart.html)
[https://regex101.com/](https://regex101.com/)

## Assignment
Create a plugin that will check comments for [the seven dirty words](https://en.wikipedia.org/wiki/Seven_dirty_words). If a comment contains any of them, translate the comment into Pig Latin when it is displayed.

If you are already familiar with regular expressions, try using <code>preg_replace</code>; otherwise, work with <code>preg_match</code> and the resultant <code>$matches</code> array.

## Additional reading
[Regex performance](http://blog.codinghorror.com/regex-performance/)
[You can't parse XHTML with regex](http://stackoverflow.com/a/1732454)
