# parse_template
Template parser

Ersetzt {{tags}} durch data.tags <br>

template = 'Ich bin {{variable}} Text'; <br>

data = {}; <br>
data.variable = 'ein'; <br>

html = parse_template (template, data); <br>

// html =  Ich bin ein Text
