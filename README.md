# ansible-cmake

A role for installing cmake.


## Actions

- Ensures that cmake is installed (using `apt`)


## Usage:
```
  - name: Install cmake
    hosts: cmake
    user: root
  #  connection: local
    
    roles:
      - cmake      
```

## License

MIT
