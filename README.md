# Flight model for HANA XSA (XS Advanced)
The classic SAP's Flight Model (SFLIGHT, SPFLI etc.) model with data as a HANA HDB module, ready for deploy in a HDI container. Useful as a starting point for people more used to it than for example SHINE.

## Tables
![Flights model](http://public_repo.vipserv.org/images/sflights-xsa/flights_model.png)

## Details
- all table definitions are in the *tables.hdbcds* file
- the context is *FlightsModel*, namespace *Flights.db*
- data imports files are in the *data* folder (.csv and .hdbtabledata files)
- some basic views in *views.hdbcds*
- prepared and tested using SAP HANA Express 2.0 SPS 04
