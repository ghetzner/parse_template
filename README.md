# parse_template
Template parser

Ersetzt {{tags}} durch array.tags <br>

template = 'Ich bin {{variable}} Text'; <br>

array = {}; <br>
array.variable = 'ein'; <br>

html = parse_template (array); <br>

# ergebnis =  Ich bin ein Text
