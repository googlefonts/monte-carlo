MonteCarlo is a beautiful formal script— both contemporary and traditional. This connecting script’s italic is slight, making it an extremely legible design.

Its additional flourishing options offer truly diverse possibilities for customization of display. MonteCarlo is perfect for those situations that require an ornate look, and a readable message, without compromising beautiful design.

## Building the Fonts

The font is built using fontmake and gftools post processing script. Tools are all python based, so it must be previously installed.

To install all the Python tools into a virtualenv, do the following:

From terminal:

```

cd your/local/project/directory

#once in the project folder create a virtual environment. 
This step has to be done just once, the first time:

python3 -m venv venv

#activate the virtual environment

source venv/bin/activate

#install the required dependencies

pip install -r requirements.txt

```

Then run the this command:

```
cd sources
gftools builder config.yml
```
