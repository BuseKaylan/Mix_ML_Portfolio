# BKaylan_Portfolio
Data Science Portfolio

# Project 1: Rock vs. Mine Classification with using KNN

df = pd.read_csv('ROCK_OR_MINE.csv')

df.head()

df.info(

def strtoint(x):
    if x == 'R':
        return 0
    else:
        return 1

df['R'] = df['R'].apply(strtoint)

X = df.drop('R', axis = 1)
y= df['R']

