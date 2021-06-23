import request

r = requests.get('https://xkcd.com/353/comics/python.png')

with open('comic.txt','w') as f:
	f.write('read me')