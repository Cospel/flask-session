# `Header` Based Flask-Session
Variant of Flask-Session, [Flask-Session](https://pypi.python.org/pypi/Flask-Session). Move cookie based approach into `Header` based apporach.

## Modifiation
Rewrite `open_session` and `save_session` function to use `Http Header` as the vehicle instead of cookie

## Configuration Honored
`SESSION_HEADER_NAME`, eg. `X-HTTP-MYFIELD`. Default is `X-Header-Session`