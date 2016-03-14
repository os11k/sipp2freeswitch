# sipp2freeswitch
sample sipp scenarios for testing freeswitch

Used following resources:

https://github.com/jrzondagh/SIPp-Scenario-Files

https://github.com/saghul/sipp-scenarios

./sipp -i local_ip_address -sf /usr/src/sipp2freeswitch/register.xml -inf /usr/src/sipp2freeswitch/register-accounts.csv destination_ip_address:5060 -r 1 -rp 1000 -aa -trace_err

./sipp -i local_ip_address -sf /usr/src/sipp2freeswitch/invite-auth.xml -inf /usr/src/sipp2freeswitch/invite-accounts.csv destination_ip_address:5060 -r 1 -rp 1000 -trace_err
