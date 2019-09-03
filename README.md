# WDT
called "weed" WDT is a watch-dog-timer system
# pja 9-2-2019
</br> Watch dog timers are spawn set and asynchronously trigger a process
</br> format:
</br> wdt.init()
</br><pre>    </pre> begins wdt agent
</br> wdt.genix()  --} generates an id
</br> wdt.set(id,seconds,process)
</br><pre>    </pre> sets a timer to go off in <bold>seconds</bold> and on explosion to run a bpx process named <bold>process</bold>.
</br> wdt.process(process)
</br><pre>    </pre> moves <bold>process</bold> to moose queue for execution
