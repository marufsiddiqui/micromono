install:
	cd account/ && npm i
	cd home/ && npm i
	cd io/ && npm i
	cd server/ && npm i && npm run-script jspm

mono:
	DEBUG=micromono* node server/server.js --service-dir ./ --service account,home

mono-io:
	DEBUG=micromono* node server/server.js --service-dir ./ --service io
