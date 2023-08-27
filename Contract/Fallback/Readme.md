`receive()` is a function that gets priority over `fallback()` when a calldata is empty. 
But fallback gets precedence over receive when calldata does not fit a valid function signature.