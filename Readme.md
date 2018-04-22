# Silly Signaling

The most basic signalling server you can get.

Don't even think about using this in production code. We recommend
[SaltyRTC][saltyrtc] for secure production signalling.

## Prerequisites

* Python 3.4+
* [pip][pip]

We recommend using [venv][venv] to create an isolated Python environment:

    python3 -m venv signaling-venv

You can switch into the created virtual environment *signaling-venv* by running
this command:

    source signaling-venv/bin/activate

While the virtual environment is active, all packages installed using
`pip` will be installed into this environment.

To deactivate the virtual environment, just run:

    deactivate

If you want easier handling of your virtualenvs, you might also want to
take a look at [virtualenvwrapper][virtualenvwrapper].

## Installation

To install the dependencies, activate the virtual environment and run

    pip install -r requirements.txt

## Usage

Run the server with the following command:

    python server.py

[saltyrtc]: https://saltyrtc.org
[pip]: https://pip.pypa.io/en/stable/installing
[venv]: https://docs.python.org/3/library/venv.html
[virtualenvwrapper]: https://virtualenvwrapper.readthedocs.io/
