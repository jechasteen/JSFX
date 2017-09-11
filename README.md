# GOALS AND INTENTIONS
The purpose of this git is to allow people to contribute their experiences and wisdom to the document. I for one think that JS is a great introduction to dsp, and can be used as a fun sandbox and learning tool. If there are any issues or corrections to the document, please post them to the issues tab. If you have a document you'd like to integrate or a simple .jsfx file, please open a pull request, or contact me via profile (jechasteen).

## JSFX Coding Guidelines
If submitting effects, please follow these guidelines for uniformity.
1. Start the file with
    desc:Effect Name
    ... other description lines
2. use comments to explain difficult to parse code, variables, algorithms, etc.
3. Leave a space after opening parenthesis and before closing parenthesis:
    x = exp( -2 / srate );
4. Leave spave between operands, operators, etc.:
    x = ( ( x - 2 ) * ( z / srate ) ) / y;
5. Use 4 spaces instead of tabs for indenting code.
    
# JSFX
## ReaperJSFX_Reference.pdf
    This is an all-in-one pdf of the JSFX reference located at <https://www.reaper.fm/sdk/js/js.php>
    I have rearranged the chapters compared to the website, corrected errors and added formatting and indexing.
## ReaperJSFX_Reference.ly
    This is the LyX file used to generate the above .pdf

## JSFX Source code
    Effects that are in parentheses are planned.
    
### (bitchanger.jsfx)
User specifies the bits, then we take each sample and bind it to one of 1/bits steps  

Disclaimer: I am not in any way affiliated with REAPER or Cockos Inc. The existence of these documents does not imply endorsement.
