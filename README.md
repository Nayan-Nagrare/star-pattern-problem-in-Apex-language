# star-pattern-problem-in-Apex-language
integer n=5;
for(integer i=1;i<=5;i++)
{
    string pattern = '';
    for(integer j=1;j<=i;j++)
    {
        pattern=pattern+'*';
    }
    system.debug(pattern);
}
