Drupal Samples
=
Currently these are just some modules I've made working with Drupal 6, with any sensitive data removed.

For breadth of Drupal API usage, take a look at mc_ux, where a bunch of common challenges are solved using simple hooks and blocks.

In a nutshell, both mc_judgecsv and mc_judgecsv_extender are super-simple functions that reference a state-change stored in a CCK value to control whether to take an action with the CCK filefield CSV associated with that same node. This way, you can change a variable, save the node and see a whole set of nodes updated, added or deleted.

By far, mc_judgedash is the least straightforward or pleasant to read. It navigates and richly themes the judging dashboard, or virtual scorecard, that judges rate contestants using. They can add new contestants to their table, and get immediate color-coded feedback and drupal-message prompts based on the custom validation script added in the hook_form_alter.


