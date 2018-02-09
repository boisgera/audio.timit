
TODO
--------------------------------------------------------------------------------

  - re-read current `audio.index` code

  - read NLTK code

  - have a look at how HTML+CSS rich display work in Jupyter.
    Javascript required for a full-fledged search? Limitations?
    (Trusted mode, etc.)

  - get a rich representation for search results, 
    alongside the textual one.

  - use the existing `.wav` files and the Media Fragments URI API
    to display players for fragments too. 

    Arf, if we refer to the wav files into an HTML embedded audio, 
    the files need to be accessible ... And if instead we base64 & embed
    them, we can't do it for ALL fragment, it needs to be on demand ...

    Do we need to tweak the `Audio` component?  
    See <https://github.com/ipython/ipython/blob/master/IPython/lib/display.py>

  - think more about the UX (search stuff, get you hand on the data, 
    "extract" it / bound it to variables, etc.)


Misc. Notes
--------------------------------------------------------------------------------

  - The DARPA TIMIT Acoustic-Phonetic Continuous Speech Corpus on Academic Torrents:

    <http://academictorrents.com/details/34e2b78745138186976cbc27939b1b34d18bd5b3>

    Nota: Orginal source <https://catalog.ldc.upenn.edu/ldc93s1>: 
    the use of TIMIT database is subject to a LDC user agreement: 
    <https://catalog.ldc.upenn.edu/license/ldc-non-members-agreement.pdf>

  - TIMIT documentation (with the CD-ROM):

    <http://nvlpubs.nist.gov/nistpubs/Legacy/IR/nistir4930.pdf>

  - TIMIT corpus (partial) in NLTK:

    <http://www.nltk.org/_modules/nltk/corpus/reader/timit.html>

    or

    <https://github.com/nltk/nltk/blob/8eb3803cb88a6e75d18d4f740678b218b3d8f4fd/nltk/corpus/reader/timit.py>

  - The TIMIT corpora is not included in NLTK by default (either pip or conda).
    On conda-forge, there is a nltk-data but it comes with all corpora
    (>400 Mo).

  - Discussion of IPython rich display (for xarray):
 
    <https://github.com/pydata/xarray/issues/1627>

