# automake1.15-perl5.22-regex-error-fix
A patch to port(fix a regex error) automake1.15 to Perl v5.22.0 and later.
It can fix such error when compile qsdk on ubuntu 18.04:
`Unescaped left brace in regex is illegal here in regex; marked by <-- HERE in m/\${ <-- HERE ([^ \t=:+{}]+)}/ at ./bin/automake.tmp line ...`

# Source
See [This link](https://github.com/XECDesign/noobs/commit/158a421ac612b248bb1507589d96d9560124675c#diff-ef89296218e21ca1ba3c88a2df722210) for the orignal commit from [XECDesign/noobs](https://github.com/XECDesign/noobs) issue[#470](https://github.com/raspberrypi/noobs/issues/470)
