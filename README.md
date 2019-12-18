



# skywalking-demo

// 指定agent.config路径

-Dskywalking_config=/path/to/agent.config

// agent配置

-DSW_AGENT_COLLECTOR_BACKEND_SERVICES=ip:port

-DSW_AGENT_NAME=sw-demo

-DSW_AGENT_THROTTLING_RATE=10000

-DDEMO_TRACE_ID_LOG_DIR=/path/to/invalidTraceIds.log


// demo配置

-DDEMO_THREAD_NUM=1

-DDEMO_INTERVAL=20


// 日志配置

-DSW_LOGGING_OUTPUT=FILE

-DSW_LOGGING_DIR=/home/xxx

-DSW_LOGGING_MAX_FILE_SIZE=314572800

-DSW_LOGGING_MAX_HISTORY_FILES=-1
