# Liscrape
Simplifying and automating Linkedin profile scraping with Python 3

**⚠️⚠️⚠️ Please use a user account that is _NOT_ your primary LinkedIn account!** Using this program through your main account could result in **account termination.**

Liscrape parses various useful bits of profile information to a spreadsheet, simplifying contact information collection quite a bit. Do note, that this is not a script that does everything for you: this is a GUI program intended for automating the copy-paste work. 

To run the program, you must first install the requirements with `pip3 install -r requirements.txt`.

Then, simply run `liscrape/liscrape/liscrape.py` through Python 3. If you need/want to bundle the program into a distributable .exe-file, use the included `build_exe.sh` file, found in `liscrape/liscrape/utils/build_exe.sh`. 


## Known issues

- The user interface locks up during operations, causing errors to appear in the logs: these can be ignored. Fix would be to use another GUI library.
