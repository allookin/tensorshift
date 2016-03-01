#TensorShift

###ABSTRACT
TensorShift is a low-level SDK allowing applications to perform disk reads/writes with fixed latency even if the data is not localized on the same HDD and event RAID-controller. TensorShift provides API and ABI for using gravitational waves to transfer data between HDDs. TensorShift supports transmission for:
* sectors
* cylinders

TensorShift may be a good support for high-troughput systems where intensive disk reads/writes are engaged. The primary benefit is that all reads in your applicatino can be localized to a single high-performance HDD. Required data from other disks (in the same RAID only supported at the moment) is synchronized via gravitational waves with polarization carrying the data payload. Radiated is sourced by spinning spindles of the source HDDs (containing required data). 

TensorShift takes responsibility for determining and coding the original data into wave parameters. Also TensorShifts takes care for radiation process planning and performing (disk daccelerations and so on).

###INTEGRATION AND USAGE
List of supported RAID controllers (tested):
TBD


###IMPLEMENTATION DETAILS

#####FUNDAMENTALS
TBD

#####DETERMINING WAVES PARAMETERS
TBD

#####RADIATION SYNC
TBD

#####DATA CONSISTENCE AND ERROR HANDLING
TBD