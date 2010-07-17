This is a Firefox bookmarklet that transform's the url of a vivo profile to the url that emits rdf. This is useful for learning about what the data in Vivo looks like as well debugging problems.

To install this bookmarklet drag this link up to your bookmark toolbar: 

<a href="javascript:loc=location.href;re=/(display|individual)\/(.+)/;location='http://'+location.host+'/individual/'+loc.match(re)[2]+'/'+loc.match(re)[2]+'.rdf'">RdifyUrl</a>

For example, running the bookmarklet while at the page: [http://vivo.ufl.edu/individual/UniversityofFlorida](http://vivo.ufl.edu/individual/UniversityofFlorida) will change the page to [http://vivo.ufl.edu/individual/UniversityofFlorida/UniversityofFlorida.rdf](http://vivo.ufl.edu/individual/UniversityofFlorida/UniversityofFlorida.rdf)

