# KiraAI_payload_defensel_plugin
LLM 注入攻击防御插件。在消息交给 LLM 之前扫描并清洗伪造的系统字段（如 QQ 消息包格式、JSON 注入等），命中后替换为拦截警告或丢弃。支持 warn/strict 双模式。
