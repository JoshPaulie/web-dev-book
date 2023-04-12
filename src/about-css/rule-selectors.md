# Selectors
In CSS, selectors are used to target specific elements in an HTML document and apply styles to them. Here are the common CSS selectors:

1. **Type** selectors: These target all elements of a particular HTML tag. For example, the selector `p` will target all `<p>` elements on a page.

2. **Class** selectors: These target elements with a specific class attribute. Class selectors start with a period (`.`) followed by the name of the class. For example, the selector `.my-class` will target all elements with the class attribute class="my-class".

3. **ID** selectors: These target a specific element with a unique ID attribute. ID selectors start with a pound sign (`#`) followed by the name of the ID. For example, the selector `#my-id` will target the element with the ID attribute `id="my-id"`.

4. **Attribute** selectors: These target elements with a specific attribute value. Attribute selectors are enclosed in brackets `[]` and contain the name of the attribute and its value. For example, the selector `[type="text"]` will target all elements with the attribute `type="text"`.

5. **Pseudo-class** selectors: These target elements based on their state or position in the document. Pseudo-classes are preceded by a colon (`:`). For example, the selector `a:hover` will target all `<a>` elements when the mouse hovers over them.

<!---- Move to own subsection

6. **Combinators**: These allow selectors to be combined in various ways to target specific elements. There are four types of combinators:
	1. the descendant combinator (` `)
	2. the child combinator (`>`)
	3. the adjacent sibling combinator (`+`)
	4. general sibling combinator (`~`)
	5. (Unofficial) the list combinator (`,`)

--->

## Chaining selectors
CSS selectors can also be chained to create complex selectors that target specific elements based on multiple criteria.

Here's an example css rule with `ul li.live` as the selector:

```css
ul li.live {
	color: red;
}
```

This rule would target all `<li>` elements that are descendants of a `<ul>` element and have the class attribute `class="live"`

> Having trouble visualizing what the html for this css rule might look like? Check out this [TODO]