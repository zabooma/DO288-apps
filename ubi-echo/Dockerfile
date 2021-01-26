FROM registry.access.redhat.com/ubi8/ubi:8.0
USER 1001
CMD bash -c "touch /tmp/a; ls -l /tmp/a; while true; do (( i++ )); echo test \$i; sleep 5; done"
