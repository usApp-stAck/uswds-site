{:.usa-content-list}
- Buttons inside of a button group follow the same guidelines as the [button component]({{ site.baseurl }}/components/button).
- Button groups support any style and size.
- Because the button group uses `flexbox`, there are several ways modify how the default button group is displayed.
  - The default button group will display as a column on smaller screen sizes. To override this behavior and display buttons in a row for all screen sizes, use the [flex-row]({{ site.baseurl }}/utilities/flex/#utility-flex-direction) utility.
  - On smaller screens, the first button in the source order will appear at the top of column. You can change this behavior using the order utility. The [order]({{ site.baseurl }}/utilities/flex/#utility-order) utility includes [responsive advanced settings]({{ site.baseurl }}/utilities/flex/#advanced-settings) that allow it to target specific screen sizes.
  - Instead of each button appearing on the left-hand side on larger screens (or if you used flex-row), you can use [flex-justify]({{ site.baseurl }}utilities/flex/#utility-flex-justify) to justify the buttons