# TODOS

- [x] Typed Literal
- [x] Make normal Literal only work for non types
- [ ] Test normal non-typed Literal
- [ ] Test TypedLiteral
- [ ] Make TypedLiteral work with isinstance: `isinstance(x, TypedLiteral[int, float]`
- [ ] TODO PEP this: `x = tuple[int | str, ...]`
- [ ] Make TypeVArTuple accept bound types, and len?!
- [ ] make `x = Literal[10]` return int(10) with a given attr like __is_literal__=True, so that `isinstance(x, int)` works, but `isinstance(0, x)` works too.