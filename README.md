# Jinja2 Snippet Extension For VS Code

This extension bundles up all your most used jinja snippets for use in your HTML templates. Also I put in a few useful ones for things like generating numbers, joining lists, and the like.


## Installation

Direct instalation is availible in the VS Code marketplace, just do a search for "Jinja2" and we should pop right up.

You can direct download the pluggin from [Marketplace Site](https://marketplace.visualstudio.com/items?itemName=WyattFerguson.jinja2-snippet-kit) 

## Usage

Usage is really simple, all the snippets are prefixed with J. Open any HTML file and type J to see a full listing of all the availible snippets.


| Prefix             | Output                     |
| ------------------- | --------------------------- |
| jblock | {% block *name* %} {% endblock *name* %} |
| jif | {% if *cond* %} {% endif %} |
| jifelse | {% if *cond* %} {% else %} {% endif %} |
| jextend | {% extends '*file*' %} |
| jfor | {% for *A* in *B* %} {% endfor %} |
| jrandom | {{ range(*MIN*, *MAX*) \| random }} |
| jvar | {{ *variable* }} |
| jfunc | {% *function* %} |
| jround | {% *float* \| round %} |
| jjoin | {% *list* \| join(',') %} |
| jset | {% set *A* = *B* %} |
| jurl | {{ url_for('*dir*', filename='*file*') }} |
| jcall | {% call *func* %} {% endcall %} |
| jfilter | {% filter *cmd* %} {% endfilter %} |
| jinclude | {% include '*file*' %} |
| jfrom | {% from '*dir*' import *func* %} |


## Version
- 1.0.0 - First working version released on vscode marketplace

## Credit and Contact

Created by Wyatt Ferguson

For any comments or questions your can reach me on Twitter [@wyattferguson](https://twitter.com/wyattferguson)


