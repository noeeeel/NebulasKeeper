# Nebulas Keeper

The application allows you to store user data in encrypted form, whether passwords or just some information.

### Smart contract

- `total()` - Returns total count of entries.

- `add(text)` - Adds a new entry.

- `update(id, text)` - Updates an existing entry.

- `delete(id)` - Deletes the entry.

- `get(limit, offset)` - Returns the specified number of entries.

- `getByWallet(wallet)` - Returns all entries of the user with the specified wallet.

