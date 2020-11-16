# Auto click script
- a simple pthon script to fire mouse click automatically in a specified interval
- it is inspired by [nitratine's blog](https://nitratine.net/blog/post/python-auto-clicker)

## Development
- clone project
```
cd workspace
git clone https://github.com/rdcwuyy/autoclick.git
cd autoclick
```

- create and/or activate conda environment

- install required modules
```
pip install -r requirements
```

## Usage
- change the settings in the script
```
    delay = 5
    button = Button.left
    start_stop_key = KeyCode(char='s')
    exit_key = KeyCode(char='e')
```

- run the script
- move your mouse to the place
- fire the start key
- fire the stop key
- fire the exit key

## License

The project source code is licensed under the [MIT license](LICENSE.md).
