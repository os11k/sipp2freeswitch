# sipp2freeswitch
sample sipp scenarios for testing freeswitch

Used following resources:

https://github.com/jrzondagh/SIPp-Scenario-Files

https://github.com/saghul/sipp-scenarios

./sipp -i local_ip_address -sf ./register.xml -inf ./register-accounts.csv destination_ip_address:5060 -r 1 -rp 1000 -aa -trace_err

./sipp -i local_ip_address -sf ./invite-auth.xml -inf ./invite-accounts.csv destination_ip_address:5060 -r 1 -rp 1000 -trace_err

./sipp -i local_ip_address -sf ./invite-without-auth.xml -inf ./invite-accounts.csv destination_ip_address:5060 -r 1 -rp 1000 -trace_err

./sipp -sf ./uas.xml -i local_ip_address -p 5060
