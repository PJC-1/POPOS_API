


POPOS (back end API)
===================
>
> This repository will contain the **Express.js** *back-end API*, which will communicate with our **React.js** *front-end* [POPOS](https://github.com/PJC-1/POPOS).
>
>

Why build this API?
-------------
> Originally I was using data from the [DataSF](https://data.sfgov.org/Culture-and-Recreation/Privately-Owned-Public-Open-Spaces/65ik-7wqd) API. But the data offered by the API was lacking consistency (i.e. a majority of the entries did not share core properties) and quality (i.e. some property entries were vague or uninformative). Here are some examples of these observations:
>

>
> An example of a description that does not provide sufficient  about the space.
```
descriptio: "Plaza with no seating."
```

>
> The data set did not have an ```id``` property, which would provide some limitations in querying/filtering.
>

>
> The data set did not contain any references to images, which would require additional work to handle.
>

----------
