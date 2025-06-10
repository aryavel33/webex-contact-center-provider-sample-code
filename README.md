# Webex Contact Center Media service APIs
## Media Service APIs
These are APIs that can be be used by AI Providers to integrate with the Webex Contact Center AI platform. Currently, we support the following use cases: 
1. BYoVA(Bring your own Virtual)- Where an AI provider can integrate their Virtual agent solution with Webex Contact Center and Webex Contact Center Enterprise (including UCCE and PCCE) via gRPC APIs.
2. Real Time Media forking (Conversation Audio)- Access real-time voice media of the conversation between the caller and the human agent by simply registering a URL with us via the "Bring your own Data Source" mechanism.


## Bring your own Virtual Agent
BYoVA can be utilized to deliver an automated and conversational IVR experience for incoming customer calls, providing a natural, life-like interaction through the use of conversational speech technology and LLM-enabled bots
Communication Protocol - gRPC
Proto defintion - voiceVirtualagent.proto(path- dialogue-connector-simulator/src/main/proto/com/cisco/wcc/ccai/media/v1)

## Real-Time Media forking
Customers or partners can utilize media forking to divert the audio from human agent-caller interactions to an external URL registered with Cisco.
Communication Protocol - gRPC
Proto defintion - conversationAudioForking.proto(path- dialogue-connector-simulator/src/main/proto/com/cisco/wcc/ccai/media/v1)

## Common concepts/frameworks used for BYoVA and Media forking-
1. Service Apps for Webex: https://developer.webex.com/create/docs/service-apps
2. Bring your own Data Source (Authentication): https://developer.webex.com/create/docs/bring-your-own-datasource
3. Bring your own Virtual Agent Guide: https://developer.webex.com/webex-contact-center/docs/bring-your-own-virtual-agent

