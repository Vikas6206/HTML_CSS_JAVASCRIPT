Combinators:

Combinator is something that explains the relationship between the selectors.

4 diffferent type of combinators in css
1] descendant selector (space)
2] child selector (>)
3] adjacent sibling selector (+)
4] general sibling selector (~)

//design delector
//matches all element that are descendants of a specified element
div p
{
	color:red;
}

// > selects all elements that are immediate children of a specified element
div > p
{
	color:green
}

// + selects all elements that are the adjacent siblings of a specified element and 'adjacent' means 'immediate following'.
sibling element must have the same parent.

div + p
{
	color:orange;
}

// ~ applies to all the siblings

div ~ p
{
	color:green;
}

