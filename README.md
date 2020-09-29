# Best FIFA 19 Team
##### By: Gustavo Pretto Scholze

Hello World! So I made this repository just-for-fun and my main objective while doing this was to put in practice my Python Data Science knowledge!

# Process of Data Cleaning
The .csv file has, originally, 89 columns, however we only used 11 (code below only has 9, but if we sum with the other 2 parameters we printed at the end, we get 11). So, instead of removing, I just created a new dataframe with the parameters I need:

    fifa = pd.DataFrame(data, columns=['Name', 'Age',
				    'Nationality', 'Club', 'Weight', 'Overall',
				    'Potential','Position', 'Jersey Number'])

# Parameters for Choosing
The parameters for choosing the best players, was based on "Overall" category and "Potential", given the best on these two attributes, we have a list containing all qualified players and their position.

Adopting a 4-3-3 scheme, we need:

> 1 GK
> 2 CB
> 1 LB and 1 RB
> 1 CDM
> 2 CM
> 1 LW and 1 RW
> 1 CF

# Conclusion

After all this process, we return a dataframe with all the top players:

Neymar Jr
De Gea
D. Godín Atlético
Sergio Busquets
S. Umtiti
Jordi Alba
Bernardo Silva
Thiago, Azpilicueta
S. Milinković-Savić

# Files

The data used in this analysis was from the FIFA19 game.

## Contact
[
![Instagram](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2F68ef2f69c7787d4078ac-7864ae55ba174c40683f10ab811d9167.ssl.cf1.rackcdn.com%2Finstagram-icon_64x64.png&f=1&nofb=1)](https://www.instagram.com/_gscholze/) [![Linkedin](https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.zraje.net%2Fimg%2Flogo%2Flogo_linkedin_small.png&f=1&nofb=1)](https://www.linkedin.com/in/gstvscholze/)
