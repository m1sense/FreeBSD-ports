PORTNAME=	miniserve
DISTVERSIONPREFIX=	v
DISTVERSION=	0.19.3
CATEGORIES=	www

MAINTAINER=	mikael@FreeBSD.org
COMMENT=	Ad-hoc HTTP server for file sharing

LICENSE=	APACHE20 BSD3CLAUSE CC0-1.0 ISCL MIT MPL20 UNLICENSE
LICENSE_COMB=	multi
LICENSE_FILE_MIT=	${WRKSRC}/LICENSE

USES=		cargo ssl:build
USE_GITHUB=	yes
GH_ACCOUNT=	svenstaro

CARGO_CRATES=	actix-codec-0.5.0 \
		actix-files-0.6.0 \
		actix-http-3.0.2 \
		actix-macros-0.2.3 \
		actix-multipart-0.4.0 \
		actix-router-0.5.0 \
		actix-rt-2.6.0 \
		actix-server-2.0.0 \
		actix-service-2.0.2 \
		actix-tls-3.0.3 \
		actix-utils-3.0.0 \
		actix-web-4.0.1 \
		actix-web-codegen-4.0.0 \
		actix-web-httpauth-0.6.0 \
		adler-1.0.2 \
		adler32-1.2.0 \
		ahash-0.7.6 \
		aho-corasick-0.7.18 \
		alloc-no-stdlib-2.0.3 \
		alloc-stdlib-0.2.1 \
		alphanumeric-sort-1.4.4 \
		ansi_term-0.12.1 \
		anyhow-1.0.56 \
		askama_escape-0.10.3 \
		assert_cmd-2.0.4 \
		assert_fs-1.0.7 \
		atty-0.2.14 \
		autocfg-1.1.0 \
		base64-0.13.0 \
		beef-0.5.1 \
		bit-set-0.5.2 \
		bit-vec-0.6.3 \
		bitflags-1.3.2 \
		block-buffer-0.10.2 \
		brotli-3.3.3 \
		brotli-decompressor-2.3.2 \
		bstr-0.2.17 \
		bumpalo-3.9.1 \
		byteorder-1.4.3 \
		bytes-1.1.0 \
		bytesize-1.1.0 \
		bytestring-1.0.0 \
		bzip2-0.4.3 \
		bzip2-sys-0.1.11+1.0.8 \
		c_linked_list-1.1.1 \
		cc-1.0.73 \
		cfg-if-1.0.0 \
		chrono-0.4.19 \
		chrono-humanize-0.2.1 \
		clap-2.34.0 \
		clap-3.1.6 \
		clap_complete-3.1.1 \
		clap_derive-3.1.4 \
		clap_mangen-0.1.2 \
		codemap-0.1.3 \
		convert_case-0.4.0 \
		cookie-0.16.0 \
		cpufeatures-0.2.1 \
		crc32fast-1.3.2 \
		crossbeam-utils-0.8.7 \
		crypto-common-0.1.3 \
		ctor-0.1.21 \
		derive_more-0.99.17 \
		diff-0.1.12 \
		difflib-0.4.0 \
		digest-0.10.3 \
		doc-comment-0.3.3 \
		either-1.6.1 \
		encoding_rs-0.8.30 \
		fastrand-1.7.0 \
		filetime-0.2.15 \
		firestorm-0.5.0 \
		flate2-1.0.22 \
		float-cmp-0.9.0 \
		fnv-1.0.7 \
		form_urlencoded-1.0.1 \
		futf-0.1.5 \
		futures-0.3.21 \
		futures-channel-0.3.21 \
		futures-core-0.3.21 \
		futures-executor-0.3.21 \
		futures-io-0.3.21 \
		futures-macro-0.3.21 \
		futures-sink-0.3.21 \
		futures-task-0.3.21 \
		futures-util-0.3.21 \
		gcc-0.3.55 \
		generic-array-0.14.5 \
		get_if_addrs-0.5.3 \
		get_if_addrs-sys-0.1.1 \
		getrandom-0.1.16 \
		getrandom-0.2.5 \
		globset-0.4.8 \
		globwalk-0.8.1 \
		grass-0.10.8 \
		h2-0.3.11 \
		hashbrown-0.11.2 \
		heck-0.4.0 \
		hermit-abi-0.1.19 \
		hex-0.4.3 \
		html5ever-0.25.1 \
		http-0.2.6 \
		http-body-0.4.4 \
		http-range-0.1.5 \
		httparse-1.6.0 \
		httpdate-1.0.2 \
		hyper-0.14.17 \
		hyper-rustls-0.23.0 \
		idna-0.2.3 \
		ignore-0.4.18 \
		indexmap-1.8.0 \
		instant-0.1.12 \
		ipnet-2.4.0 \
		itertools-0.10.3 \
		itoa-1.0.1 \
		jobserver-0.1.24 \
		js-sys-0.3.56 \
		language-tags-0.3.2 \
		lasso-0.5.1 \
		lazy_static-1.4.0 \
		libc-0.2.119 \
		libflate-1.1.2 \
		libflate_lz77-1.1.0 \
		local-channel-0.1.2 \
		local-waker-0.1.2 \
		lock_api-0.4.6 \
		log-0.4.14 \
		mac-0.1.1 \
		markup5ever-0.10.1 \
		markup5ever_rcdom-0.1.0 \
		matches-0.1.9 \
		maud-0.23.0 \
		maud_macros-0.23.0 \
		memchr-2.4.1 \
		mime-0.3.16 \
		mime_guess-2.0.4 \
		miniz_oxide-0.4.4 \
		mio-0.8.0 \
		miow-0.3.7 \
		nanoid-0.4.0 \
		new_debug_unreachable-1.0.4 \
		normalize-line-endings-0.3.0 \
		ntapi-0.3.7 \
		num-bigint-0.4.3 \
		num-integer-0.1.44 \
		num-rational-0.4.0 \
		num-traits-0.2.14 \
		num_cpus-1.13.1 \
		num_threads-0.1.3 \
		once_cell-1.10.0 \
		os_str_bytes-6.0.0 \
		output_vt100-0.1.3 \
		parking_lot-0.11.2 \
		parking_lot-0.12.0 \
		parking_lot_core-0.8.5 \
		parking_lot_core-0.9.1 \
		paste-1.0.6 \
		percent-encoding-2.1.0 \
		phf-0.8.0 \
		phf-0.9.0 \
		phf_codegen-0.8.0 \
		phf_generator-0.8.0 \
		phf_generator-0.9.1 \
		phf_macros-0.9.0 \
		phf_shared-0.8.0 \
		phf_shared-0.9.0 \
		phf_shared-0.10.0 \
		pin-project-lite-0.2.8 \
		pin-utils-0.1.0 \
		pkg-config-0.3.24 \
		port_check-0.1.5 \
		ppv-lite86-0.2.16 \
		precomputed-hash-0.1.1 \
		predicates-2.1.1 \
		predicates-core-1.0.3 \
		predicates-tree-1.0.5 \
		pretty_assertions-1.2.0 \
		proc-macro-error-1.0.4 \
		proc-macro-error-attr-1.0.4 \
		proc-macro-hack-0.5.19 \
		proc-macro2-1.0.36 \
		qrcodegen-1.7.0 \
		quote-1.0.15 \
		rand-0.7.3 \
		rand-0.8.5 \
		rand_chacha-0.2.2 \
		rand_chacha-0.3.1 \
		rand_core-0.5.1 \
		rand_core-0.6.3 \
		rand_hc-0.2.0 \
		rand_pcg-0.2.1 \
		redox_syscall-0.2.11 \
		regex-1.5.5 \
		regex-automata-0.1.10 \
		regex-syntax-0.6.25 \
		remove_dir_all-0.5.3 \
		reqwest-0.11.10 \
		ring-0.16.20 \
		rle-decode-fast-1.0.3 \
		roff-0.2.1 \
		rstest-0.12.0 \
		rustc_version-0.4.0 \
		rustls-0.20.4 \
		rustls-pemfile-0.3.0 \
		rustversion-1.0.6 \
		ryu-1.0.9 \
		same-file-1.0.6 \
		scopeguard-1.1.0 \
		sct-0.7.0 \
		select-0.5.0 \
		semver-1.0.6 \
		serde-1.0.136 \
		serde_derive-1.0.136 \
		serde_json-1.0.79 \
		serde_urlencoded-0.7.1 \
		sha-1-0.10.0 \
		sha2-0.10.2 \
		signal-hook-registry-1.4.0 \
		simplelog-0.11.2 \
		siphasher-0.3.10 \
		slab-0.4.5 \
		smallvec-1.8.0 \
		socket2-0.4.4 \
		spin-0.5.2 \
		string_cache-0.8.3 \
		string_cache_codegen-0.5.1 \
		strsim-0.8.0 \
		strsim-0.10.0 \
		strum-0.24.0 \
		strum_macros-0.24.0 \
		syn-1.0.86 \
		tar-0.4.38 \
		tempfile-3.3.0 \
		tendril-0.4.2 \
		termcolor-1.1.3 \
		terminal_size-0.1.17 \
		termtree-0.2.4 \
		textwrap-0.11.0 \
		textwrap-0.15.0 \
		thiserror-1.0.30 \
		thiserror-impl-1.0.30 \
		thread_local-1.1.4 \
		time-0.1.43 \
		time-0.3.7 \
		time-macros-0.2.3 \
		tinyvec-1.5.1 \
		tinyvec_macros-0.1.0 \
		tokio-1.17.0 \
		tokio-rustls-0.23.2 \
		tokio-util-0.6.9 \
		tokio-util-0.7.0 \
		tower-service-0.3.1 \
		tracing-0.1.31 \
		tracing-core-0.1.22 \
		try-lock-0.2.3 \
		twoway-0.2.2 \
		typenum-1.15.0 \
		unchecked-index-0.2.2 \
		unicase-2.6.0 \
		unicode-bidi-0.3.7 \
		unicode-normalization-0.1.19 \
		unicode-width-0.1.9 \
		unicode-xid-0.2.2 \
		untrusted-0.7.1 \
		url-2.2.2 \
		utf-8-0.7.6 \
		vec_map-0.8.2 \
		version_check-0.9.4 \
		wait-timeout-0.2.0 \
		walkdir-2.3.2 \
		want-0.3.0 \
		wasi-0.9.0+wasi-snapshot-preview1 \
		wasi-0.10.2+wasi-snapshot-preview1 \
		wasm-bindgen-0.2.79 \
		wasm-bindgen-backend-0.2.79 \
		wasm-bindgen-futures-0.4.29 \
		wasm-bindgen-macro-0.2.79 \
		wasm-bindgen-macro-support-0.2.79 \
		wasm-bindgen-shared-0.2.79 \
		web-sys-0.3.56 \
		webpki-0.22.0 \
		webpki-roots-0.22.2 \
		winapi-0.2.8 \
		winapi-0.3.9 \
		winapi-i686-pc-windows-gnu-0.4.0 \
		winapi-util-0.1.5 \
		winapi-x86_64-pc-windows-gnu-0.4.0 \
		windows-sys-0.32.0 \
		windows_aarch64_msvc-0.32.0 \
		windows_i686_gnu-0.32.0 \
		windows_i686_msvc-0.32.0 \
		windows_x86_64_gnu-0.32.0 \
		windows_x86_64_msvc-0.32.0 \
		winreg-0.10.1 \
		xattr-0.2.2 \
		xml5ever-0.16.2 \
		yansi-0.5.0 \
		zip-0.5.13 \
		zstd-0.10.0+zstd.1.5.2 \
		zstd-safe-4.1.4+zstd.1.5.2 \
		zstd-sys-1.6.3+zstd.1.5.2

PLIST_FILES=	bin/miniserve
PORTDOCS=	README.md

OPTIONS_DEFINE=	DOCS

post-install:
	${STRIP_CMD} ${STAGEDIR}${PREFIX}/bin/miniserve

post-install-DOCS-on:
	@${MKDIR} ${STAGEDIR}${DOCSDIR}
	${INSTALL_MAN} ${WRKSRC}/README.md ${STAGEDIR}${DOCSDIR}

.include <bsd.port.mk>
