# Poc_Fuzzing
Store the POCs of fuzzing.
### CVE-2022-23850

*Base Score: 7.8 HIGH*   
*Vector:  CVSS:3.1/AV:L/AC:L/PR:N/UI:R/S:U/C:H/I:H/A:H*

xhtml_translate_entity in xhtml.c in epub2txt (aka epub2txt2) through 2.02 allows a stack-based buffer overflow via a crafted EPUB document.
#### Reference:
 - https://nvd.nist.gov/vuln/detail/CVE-2022-23850
 - https://github.com/kevinboone/epub2txt2/issues/17
