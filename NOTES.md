# Project Notes

## Assumptions

- The application manages one rotating susu savings group.

## Design decisions

- Keep CLI, models, repositories, services, and money utilities in separate modules.
- Represent money as integer pesewas.
- Use in-memory storage initially.

## Limitations

- Business operations and persistence are not implemented yet.

## Future improvements

- Add group and member management, contributions, week closure, payouts, and reports.
- Consider persistent storage after the initial in-memory implementation.
