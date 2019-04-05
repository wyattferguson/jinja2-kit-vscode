# Jinja2 Snippet Extension For VS Code

This extension bundles up all your most used jinja snippets for use in your HTML templates. Also I put in a few useful ones for things like generating numbers, joining lists, and the like.

## Installation

1. Download this nice extension

2. Copy it into <code>.vscode/extensions</code>

3. Restart VSCode 

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



