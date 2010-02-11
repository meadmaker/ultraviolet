# Ultraviolet

[Ultraviolet][1] is a syntax highlighting library and engine. It uses 
[TextMate][2] syntax files and parses them using the [Textpow][3] library.
It supports more than 60 programming languages out of the box.

[1]:http://ultraviolet.rubyforge.org/index.xhtml
[2]:http://macromates.com/
[3]:http://textpow.rubyforge.org

## SYNTAX

See [usage][4].

[4]:http://ultraviolet.rubyforge.org/usage.xhtml

## REQUIREMENTS:

* [Oniguruma][5] for Ruby v1.1.0 or higher.
* [Textpow][6] v0.9.0 or higher.

[5]:http://oniguruma.rubyforge.org
[6]:http://textpow.rubyforge.org

## INSTALL:

`sudo gem install --source http://gemcutter.org hyperbolist-ultraviolet`

## SUPPORTED LANGUAGES

    actionscript, active4d, active4d_html, active4d_ini, active4d_library, ada,
    antlr, apache, applescript, asp, asp_vb.net, bibtex, blog_html, blog_markdown,
    blog_text, blog_textile, build, bulletin_board, c++, c, cake, camlp4, cm,
    coldfusion, context_free, cs, css, css_experimental, csv, d, diff, dokuwiki,
    dot, doxygen, dylan, eiffel, erlang, f-script, fortran, fxscript, greasemonkey,
    gri, groovy, gtd, gtdalt, haml, haskell, html-asp, html, html_django,
    html_for_asp.net, html_mason, html_rails, html_tcl, icalendar, inform, ini,
    installer_distribution_script, io, java, javaproperties, javascript,
    javascript_+_prototype, javascript_+_prototype_bracketed, jquery_javascript,
    json, languagedefinition, latex, latex_beamer, latex_log, latex_memoir,
    lexflex, lighttpd, lilypond, lisp, literate_haskell, logo, logtalk, lua, m,
    macports_portfile, mail, makefile, man, markdown, mediawiki, mel, mips,
    mod_perl, modula-3, moinmoin, mootools, movable_type, multimarkdown,
    objective-c++, objective-c, ocaml, ocamllex, ocamlyacc, opengl, pascal, perl,
    php, plain_text, pmwiki, postscript, processing, prolog, property_list, python,
    python_django, qmake_project, qt_c++, quake3_config, r, r_console, ragel,
    rd_r_documentation, regexp, regular_expressions_oniguruma,
    regular_expressions_python, release_notes, remind, restructuredtext, rez, ruby,
    ruby_experimental, ruby_on_rails, s5, scheme, scilab, setext,
    shell-unix-generic, slate, smarty, sql, sql_rails, ssh-config, standard_ml,
    strings_file, subversion_commit_message, sweave, swig, tcl, template_toolkit,
    tex, tex_math, textile, tsv, twiki, txt2tags, vectorscript, xhtml_1.0, xml,
    xml_strict, xsl, yaml, yui_javascript

## SUPPORTED THEMES

    active4d, all_hallows_eve, amy, barf, bbedit, bespin, black_pearl,
    black_pearl_ii, blackboard, blacklight, boysandgirls01, brilliance_black,
    brilliance_dull, choco, classic_modified, clouds, clouds_midnight, cobalt,
    coda, cool_glow, dawn, django, django_smoothy, dominion_day, eclips3media_eclm,
    eiffel, emacs, espresso_libre, fake, fluidvision, frekar, github, happydeluxe,
    idle, idlefingers, ilife_05, iplastic, ir_black, ir_white, lazy, mac_classic,
    made_of_code, magicwb_amiga, merbivore, merbivore_soft, midnight,
    minimal_theme, mintblue, mintblue_dark, monoindustrial, monokai,
    monokai_for_textmaters_custom, notepad2, overcast, pastels_on_dark,
    plasticcodewrap, railscasts, rubyblue, sin_city_2, slush_poppies, smoothy,
    smurfy, spacecadet, starlight, sunburst, swyphs_ii, tango, tek, texari,
    text_ex_machina, twilight, twilight_bg_fg, upstream, upstream_sunburst,
    upstream_vibrant, vibrant_ink, whys_poignant, zenburnesque

## THEME PREVIEWS

From versions <= 0.10.2

* [Ultraviolet Theme Gallery](http://ultraviolet.rubyforge.org/themes.xhtml)

From versions >= 0.10.202

* [TextMate User-Submitted Themes](http://wiki.macromates.com/Themes/UserSubmittedThemes)
* [VibrantInk](http://alternateidea.com/blog/articles/2006/01/03/textmate-vibrant-ink-theme-and-prototype-bundle)
* [GitHub Theme](http://github.com/blog/73-github-textmate-theme)

From versions >= 0.10.203

* [RailsCasts Theme](http://railscasts.com/about)

## COPY CSS

`ruby -rubygems -e "require 'uv'; Uv.copy_files 'xhtml', '/where/to/copy'"`

Alternatively you can find all of the css in `render/xhtml/files/css` wherever
this gem is installed.

## BROKEN THEMES

The following themes are relatively broken in terms of how background colors
are handled for transparencies.  Hand-editing the css is recommended.

* `eclips3media_eclm`
* `ilife_05`
* `mintblue`
* `mintblue_dark`
* `monokai_for_textmaters_custom`
* `sin_city_2`
* `twilight_bg_fg`

## BUGS/PROBLEMS/INCOMPATIBILITIES:

## TODO:

## CREDITS:

* [Dizan Vasquez][7] is the original author of [Ultraviolet][8].
* [Guillaume Maury][9] brought the project to [github][10].
* [Eric Sherman][11] added themes and pushed a [gem][12].

[7]:http://dizanvasquez.net/
[8]:http://ultraviolet.rubyforge.org/index.xhtml
[9]:http://gom-jabbar.org/
[10]:http://github.com/giom/ultraviolet
[11]:http://github.com/hyperbolist
[12]:http://gemcutter.org/gems/hyperbolist-ultraviolet

## LICENSE:

(The MIT License)

    Copyright (c) 2007-2010 Dizan Vasquez

    Permission is hereby granted, free of charge, to any person obtaining
    a copy of this software and associated documentation files (the
    'Software'), to deal in the Software without restriction, including
    without limitation the rights to use, copy, modify, merge, publish,
    distribute, sublicense, and/or sell copies of the Software, and to
    permit persons to whom the Software is furnished to do so, subject to
    the following conditions:

    The above copyright notice and this permission notice shall be
    included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
    IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
    CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
    TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
    SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
