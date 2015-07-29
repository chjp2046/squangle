cc_library(
    name = "squangle",
    srcs = [
		'logger/DBEventCounter.cpp',
		'logger/DBEventLogger.cpp',
		'mysql_client/AsyncConnectionPool.cpp',
		'mysql_client/AsyncHelpers.cpp',
		'mysql_client/AsyncMysqlClient.cpp',
		'mysql_client/Connection.cpp',
		'mysql_client/DbResult.cpp',
		'mysql_client/FutureAdapter.cpp',
		'mysql_client/OperationBatch.cpp',
		'mysql_client/Operation.cpp',
		'mysql_client/Query.cpp',
		'mysql_client/Row.cpp',
    ],
    deps = [
        '//folly:folly',
        '//thirdparty/mysql:webscalesqlclient_r'
    ],
    warning = 'no'
)
