```
root@n206-079-028:/data00/wenhui/kvm-unit-tests# ./run_tests.sh 
FAIL apic-split 
PASS ioapic-split (19 tests)
FAIL x2apic 
FAIL xapic 
FAIL ioapic (timeout; duration=90s)
SKIP cmpxchg8b (i386 only)
PASS smptest (1 tests)
PASS smptest3 (1 tests)
PASS vmexit_cpuid 
FAIL vmexit_vmcall 
PASS vmexit_mov_from_cr8 
PASS vmexit_mov_to_cr8 
PASS vmexit_inl_pmtimer 
PASS vmexit_ipi 
PASS vmexit_ipi_halt 
PASS vmexit_ple_round_robin 
PASS vmexit_tscdeadline 
PASS vmexit_tscdeadline_immed 
PASS vmexit_cr0_wp 
PASS vmexit_cr4_pge 
FAIL access (timeout; duration=90s)
SKIP access-reduced-maxphyaddr (/sys/module/kvm_intel/parameters/allow_smaller_maxphyaddr not equal to Y)
PASS smap (18 tests)
PASS pku (7 tests)
SKIP pks (0 tests)
SKIP asyncpf (0 tests)
FAIL emulator (timeout; duration=90s)
PASS eventinj (13 tests)
FAIL hypercall 
FAIL idt_test 
PASS memory (7 tests)
FAIL msr 
SKIP pmu (/proc/sys/kernel/nmi_watchdog not equal to 0)
SKIP pmu_lbr (/proc/sys/kernel/nmi_watchdog not equal to 0)
SKIP pmu_pebs (/proc/sys/kernel/nmi_watchdog not equal to 0)
SKIP vmware_backdoors (/sys/module/kvm/parameters/enable_vmware_backdoor not equal to Y)
FAIL realmode 
FAIL s3 
PASS setjmp (10 tests)
PASS sieve 
PASS syscall (2 tests)
PASS tsc (3 tests)
SKIP tsc_adjust (1 tests, 1 skipped)
PASS xsave (15 tests)
PASS rmap_chain 
FAIL svm (timeout; duration=90s)
SKIP svm_pause_filter (1 tests, 1 skipped)
SKIP svm_npt (1 tests, 1 skipped)
SKIP taskswitch (i386 only)
SKIP taskswitch2 (i386 only)
FAIL kvmclock_test 
FAIL pcid-enabled (2 tests, 1 unexpected failures)
FAIL pcid-disabled (2 tests, 1 unexpected failures)
FAIL pcid-asymmetric (2 tests, 1 unexpected failures)
PASS rdpru (1 tests)
PASS umip (11 tests)
SKIP la57 (i386 only)
SKIP vmx (0 tests)
SKIP ept (0 tests)
SKIP vmx_eoi_bitmap_ioapic_scan (0 tests)
SKIP vmx_hlt_with_rvi_test (0 tests)
SKIP vmx_apicv_test (0 tests)
SKIP vmx_apic_passthrough_thread (0 tests)
SKIP vmx_init_signal_test (0 tests)
SKIP vmx_sipi_signal_test (0 tests)
SKIP vmx_apic_passthrough_tpr_threshold_test (0 tests)
SKIP vmx_vmcs_shadow_test (0 tests)
SKIP vmx_pf_exception_test (0 tests)
SKIP vmx_pf_vpid_test (0 tests)
SKIP vmx_pf_invvpid_test (0 tests)
SKIP vmx_pf_no_vpid_test (0 tests)
SKIP vmx_pf_exception_test_reduced_maxphyaddr (/sys/module/kvm_intel/parameters/allow_smaller_maxphyaddr not equal to Y)
FAIL debug (timeout; duration=90s)
SKIP hyperv_synic 
SKIP hyperv_connections (1 tests, 1 skipped)
PASS hyperv_stimer (1 tests)
SKIP hyperv_clock (1 tests, 1 skipped)
PASS intel_iommu (11 tests)
SKIP tsx-ctrl (1 tests, 1 skipped)
SKIP intel_cet (qemu-system-x86_64: failed to initialize KVM: No such file or directory)

```
