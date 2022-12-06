# config-cht-demo

_NOTE: this implementation is for demonstration purposes only. It is not intended for actual usage or as a guide for recommended UX practices._

Re-imagined implementations of the [default forms](https://github.com/medic/cht-core/tree/master/config/default).

## `delivery`

Incomplete rewrite of the `delivery` form to demonstrate various new Enketo features available in CHT `4.0.0`.

### Notable features

- Likert scale-style `select_one` question widgets
  - There are several additional new widgets available to enhance select questions
- Range slider question widgets
  - There are several additional new widgets available to enhance numeric questions
- Markdown styling in `question` and `group` labels (not just `note`s)
- `columns-*` appearances
- "Button style" select questions with image choices but no label
- Enhanced `repeat` functionality:
  - Dynamically calculated `repeat_count`
  - Support for `count` and `position` functions

### Currently not implemented

- Death workflow for mother
- Death workflow for baby
- Contact doc creation for new babies
