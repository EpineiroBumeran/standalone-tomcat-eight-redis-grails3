# standalone-tomcat-eight-redis-grails3
make redis the default session manager for tomcat 8. This plugin is for Grails 3

# Configuration

grails.plugin.standalone.tomcat.redis.redisHostname

	Redis server host

grails.plugin.standalone.tomcat.redis.redisPassword

	Redis server password

grails.plugin.standalone.tomcat.redis.redisPort

	Redis server port
	
grails.plugin.standalone.tomcat.redis.redisTimeout

	Redis conecction timeout (in millis)

grails.plugin.standalone.tomcat.redis.maxActiveSessions

	Max active sessions (default -1 = unlimited)

grails.plugin.standalone.tomcat.redis.maxInactiveInterval

	Max inactive interval (in seconds, default 30 mins)
	
grails.plugin.standalone.tomcat.redis.sessionIdLength

	Session id Length
