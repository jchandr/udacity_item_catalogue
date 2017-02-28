To start this website up:

1. Download or clone the `p3/vagrant` directory.
2. Initialize the Vagrant vm via `vagrant up`, which should set up on `localhost:5000`.
3. Connect to the virtual machine: `vagrant ssh`.
4. Start the server: `python application.py`.
5. Navigate to it in your browser of choice at `localhost:5000`.  The first-time run of the server will initialize the database with fixture data.