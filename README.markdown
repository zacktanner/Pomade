# Pomade

Pomodoro tracking on the wrist. More to come, hopefully. See `TODO.markdown`.

To clone and hack:

    git clone https://github.com/jonspeicher/Pomade.git
    <pebble-sdk-root>/Pebble/tools/create_pebble_project.py --symlink-only <pebble-sdk-root>/Pebble/sdk Pomade
    cd Pomade && ./waf configure && ./waf build