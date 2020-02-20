# Center tabs on Elementor
Did you ever need to use the Elementor tabs widget (or Tabs), and needed to center the tabs, but did not find these options in the widget? (unfortunately this option does not even exist in the Widget).

Yeah, you’re not the only one. I have received this doubts on social networks and through our consultancy. So, without much fanfare, let’s get the solution!

It’s simple, you’ll need to use CSS code that can be inserted into the Elementor widget itself (if you’re using the PRO version) or the CSS editor for your theme.

```
.elementor-tabs-wrapper {
display: flex;
justify-content: center;
}
```

