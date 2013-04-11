# TIMMIT v1.0

The Tried Intelligent Methods Met Impossible Trolls Waiver (TIMMIT) is a piece of semi-serious, but **not legally binding** dark humor.

```html
<!-- Code sample from http://codecrap.com/content/743/ -->
<form>
    Login : <input type=textbox name=login><br>
    Password : <input type=password name=pass><br>
    <input type=button value="OK" onCLick="if (login.value=='admin'&&pass.value=='123456') window.location.replace('admin.php'); ">
</form>
```

![This is not how it's done](http://media.tumblr.com/2f97c667249a55cd90116bfa73b60d3d/tumblr_inline_misskuTgjp1qz4rgp.gif)

Include this file in your software project to lighten your conscience when you're forced to write or maintain low quality, untested code.

# Usage

Include the [WAIVER.md](https://github.com/anroots/timmit/blob/master/WAIVER.md) file in your project root directory.

If the project is publicly accessible from the web, consider adding a server exception so that the file could not be reached via direct HTTP.

Do not use this if it is within your power to make things better but you're just lazy or unwilling to learn.

## Use Cases

Use when...

* The [Project Management Triangle](http://en.wikipedia.org/wiki/Project_management_triangle) get blatantly ignored either by the client and/or the manager at project inception or during a sprint
* You're taking over maintenence / development of a codebase that is a mess
* Your technical expertise and advise is ignored by the business side
* You sincerely believe that the projects ultimate doom is caused by other stakeholders and you've done all you can to save it

# What You Can Do

To improve the codebase so that the waiver would not be neccessary...

1. Rebuild the thing from scratch (altho [not always the most practical thing to do](http://unassumingphp.com/rock-on-refactor-or-re-roll/))
2. If not possible, [Refactor All The F***ing Time](http://www.youtube.com/watch?v=y5k8JyaFBZk).

# Contribute

Modify the waiver text as you see fit (fix typos, add sections / clauses) and send a pull request. The text was based on [the MIT license](http://opensource.org/licenses/MIT).